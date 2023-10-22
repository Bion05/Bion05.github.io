# Bion05.github.io
# Check out solution URL
$ cat solution.txt
Bion05.github.io
# Ensure the URL exists
$ curl --output /dev/null --silent --head --fail Bion05.github.io \
&& echo "URL exists" || echo "URL does not exist"