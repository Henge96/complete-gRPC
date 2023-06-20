gen:
	protoc --proto_path=proto --go_out=plugins=grpc:pb proto/*.proto
clean:
	rm pb/*.go
run:
	go run main.go
