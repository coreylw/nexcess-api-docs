serve-docs:
	docker run -it --rm --name nexcess-docs -p 8080:80 \
		-v ${PWD}/api.yaml:/usr/share/nginx/html/api.yaml \
		-e SPEC_URL=api.yaml redocly/redoc