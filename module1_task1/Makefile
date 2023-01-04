build :
	hugo -D > /dev/null 2>&1

.PHONY: clean
clean :
	rm -rf ./dist/ > /dev/null 2>&1

post :
	hugo new posts/$(POST_NAME).md
