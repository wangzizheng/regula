notes/ contains the ebnf for constraint annotations.
scaffold/ contains HTML for qunit test pages and for sandbox HTML pages where I can play around and debug stuff using tracegl
src/ contains the source code for the project along with third-party libraries

build.sh will build a complete, optimized distribution of the project.
test-build.sh will build a complete distribution that has NOT been optimized, which makes debugging easier during tests.
start-test-env.sh will start up a running test-environment. You can run tests and view coverage using JSCover. You can also trace your code if you have tracegl.
