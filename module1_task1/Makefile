build :
	hugo -D > /dev/null 2>&1

.PHONY: clean
clean :
	rm -rf ./dist/ > /dev/null 2>&1

post :
	hugo new posts/$(POST_NAME).md
	echo '---\ntitle: "$(POST_TITLE)"\ndate: 2023-01-04T17:03:41+01:00\ndraft: false\n---' > ./content/posts/$(POST_NAME).md

