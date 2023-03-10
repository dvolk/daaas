This readme details how to deploy the daaas platform with docker

## Configuration

Gather the daaas configuration files and put them into the following structure

```
config/
├── admin-panel
│   ├── downtime_register.json
│   ├── jwt.key
│   ├── jwt.key.pub
│   ├── local_maintenance_calendar.json
│   ├── local_service_info.json
│   ├── platform-key
│   └── server.ini
└── workspace-register
    └── workspace-register.ini
```

## Run

```
docker-compose up
```

## Open admin panel

open http://localhost:8001
