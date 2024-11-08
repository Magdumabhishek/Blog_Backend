{
	"info": {
		"_postman_id": "5aab1d70-2855-4922-a73f-7a16f8d0904d",
		"name": "Blog_Backend",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json",
		"_exporter_id": "39559616"
	},
	"item": [
		{
			"name": "get user",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "https://blog-backend-8jle.onrender.com/api/user",
					"protocol": "https",
					"host": [
						"blog-backend-8jle",
						"onrender",
						"com"
					],
					"path": [
						"api",
						"user"
					]
				}
			},
			"response": []
		},
		{
			"name": "post user",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"name\":\"Abhishek\",\r\n    \"email\":\"magdumahbishek8@gmail.com\",\r\n    \"password\":\"Abhi@123\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://blog-backend-8jle.onrender.com/api/user",
					"protocol": "https",
					"host": [
						"blog-backend-8jle",
						"onrender",
						"com"
					],
					"path": [
						"api",
						"user"
					]
				}
			},
			"response": []
		},
		{
			"name": "get blog",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "https://blog-backend-8jle.onrender.com/api/blog",
					"protocol": "https",
					"host": [
						"blog-backend-8jle",
						"onrender",
						"com"
					],
					"path": [
						"api",
						"blog"
					]
				}
			},
			"response": []
		},
		{
			"name": "post blog",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"title\":\"Dandoba Trek\",\r\n    \"content\":\"recently visited to Dandoba hills for trek............\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://blog-backend-8jle.onrender.com/api/blog",
					"protocol": "https",
					"host": [
						"blog-backend-8jle",
						"onrender",
						"com"
					],
					"path": [
						"api",
						"blog"
					]
				}
			},
			"response": []
		}
	]
}
