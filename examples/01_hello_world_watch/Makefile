install_babel:
	npm install --global --update babel-cli
	npm install

download_react:
	curl -s -L https://fb.me/react-0.14.2.js -o react.js
	curl -s -L https://fb.me/react-dom-0.14.2.js -o react-dom.js

compile:
	babel --watch src --out-dir build
