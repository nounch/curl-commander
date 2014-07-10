# Curl Commander

This script lets you manually

- test `curl` implementations or
- test various `curl` presets.

It does that by sending common HTTP requests to
[httpbin.org](http://httpbin.org/)
.

## Usage

1. Either point the `curlcommand` function's `curl` invocation to your
   specific `curl` implementation or change the `curl` invocation to use
   your presets. Then run the `curlcommander` script.

   Alternatively you can just alias `curl` before running the
   `curlcommander` script so you do not have to fiddle with the script at
   all.

2. Customize the requests by commenting out lines on the fly.

3. Then inspect the output.
