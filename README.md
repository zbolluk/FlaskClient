## Running the code on your development server

1. Create and activate a virtual environment, install everything from requirements.txt

2. Run hub

    > python hub.py

3. Run the channel server (different shell)

    > python channel.py

4. Register the channel server with the hub (another different shell)

    > flask --app channel.py register
    
5. Now start the client (new shell of shell from 4.) 

    > python client.py

6. Open the client, link is displayed after client start (e.g., http://localhost:5005)


But don't forget to register your channel server with the hub (see above).
