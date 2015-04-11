# simpleRestServer

Really simple restful service for development and test environment. Developed with Python script.

To start the service, just run...

	python server.py 0.0.0.0 8001
	 
Or simply issue command...

	python server.py
	
The server will start with port 8000

I provide startup script that print out help while service is starting. Just issue command...

	./server.sh

For Windows, try Google for batch script.

The service supported GET and POST methods. To use service. Create plain text file with JSON document and put it in the same folder of the server.py file. Then request to the file like :-

	http://localhost:8000/result.json

Press Ctrl+C to stop the server.

Hope this help. 
Have fun.