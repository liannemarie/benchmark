run: build
	docker run -v `pwd`:/repo cargo-audit > output.txt 2>&1 || true

build:
	docker build -t cargo-audit .

