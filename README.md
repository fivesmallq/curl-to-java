curl-to-java
===========

curl-to-java is a tool to instantly convert [curl](http://curl.haxx.se) commands to Java code in the browser. It does *not* guarantee high-fidelity conversions, but it's good enough for most API docs that have curl samples.


### Try it

**[Check it out!](https://fivesmallq.github.io/curl-to-java)** It works inside your browser. Just give the code a once-over since it will need you to flush out some parts like error handling.


### FAQ

#### Does any curl command work?

Any curl command should work, but only certain flags are understood and converted into Java code. The rest of the flags will be ignored.

#### Which kinds of curl commands are understood?

Mostly simple HTTP commands (headers, basic auth, body, etc).

#### Will you consider supporting *this-or-that* flag?

curl has like a bajillion options, so don't expect all of them to be implemented; just the most common/important ones to stub out code from API samples and docs, etc. But feel free to open an issue or submit a pull request! To request a new flag, please provide the equivalent Go code.



### Credits

curl-to-Go is brought to you by Matt Holt ([mholt6](https://twitter.com/mholt6)). Enjoy!

curl-to-php is brought to you by John C ([John C](https://github.com/incarnate/curl-to-php)). Enjoy!

