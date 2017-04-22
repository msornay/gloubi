
CONTAINER = gloubi/tor

container:
	docker build -t $(CONTAINER) .

shell:
	docker run -it --rm --entrypoint=/bin/ash $(CONTAINER)

.PHONY: container
