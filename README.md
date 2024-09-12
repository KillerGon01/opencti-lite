# OpenCTI-Lite
A new version of DISARM Red Framework dedicated to social media.

## Configuration
In the ''/opencti/docker-compose.yml'' file, set the connector from disarm lite (the last one added).

In the ''.env'' file, you have to add your disarm-lite.json. You can create it and then upload it to Git-Hub. Finally, copy the raw URL to the ''URL_DISARM_LITE'' variable.

## Initialization

In the ''/opencti'' run the command:
```
docker-compose up --build
```

Once it is loaded, open a new tab on your browser and go to:
```
localhost:8080
```

Log in with your credentials (they are in the ''.env'' file, ''OPENCTI_ADMIN_EMAIL'' and ''OPENCTI_ADMIN_PASSWORD'').

When you are in the opencti platform, you can create a new ''incident response'' and when it is created, you can click on it navigate into the ''knowledge'' section and click in the ''Tactics matrix view'' (at the top right). 

Finally, change the matrix at the bottom left and you will see your matrix loaded.