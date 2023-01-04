build :
	hugo -D > /dev/null 2>&1

.PHONY: clean
clean :
	rm -rf ./dist/ > /dev/null 2>&1

post :
	hugo new posts/$(POST_NAME).md
	echo  ' ---\ntitle: "$(POST_TITLE)"\ndate: 2023-01-04T19:38:24+01:00\ndraft: false\n--- '  >  ./contenu/articles/ $( POST_NAME ) .md
