### CMD:
- docker build . -f "Dockerfile1"
### Output Errors:
- google/protobuf/Timestamp.proto : error : File not found. [/src/mymy/mymy.csproj]
- Protos/notification.proto(4,1): error : Import "google/protobuf/Timestamp.proto" was not found or had errors. [/src/mymy/mymy.csproj]
- Protos/notification.proto(112,5): error : "google.protobuf.Timestamp" is not defined. [/src/mymy/mymy.csproj]