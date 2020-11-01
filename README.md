# version
version and tagging

# run on command line
 mvn --batch-mode release:clean release:prepare release:perform -Darguments="-Dmaven.javadoc.skip=true -Dmaven.test.skipTests=true -Dmaven.test.skip=true" -Dusername={GIT_USER} -Dpassword={GIT_PASSWORD}
