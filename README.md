# Node.js Essential Packages <a href="https://img.shields.io/badge/npm-essentials-ff69b4.svg"><img src="https://img.shields.io/badge/npm-essentials-ff69b4.svg" /></a>

[Adrian's](https://twitter.com/adriancbo) collection of super useful NPM packages.

## Utilities

#### Async

- [async](https://www.npmjs.com/package/async) - Higher-order functions and common patterns for asynchronous code.

#### Buffers

- [binary](https://www.npmjs.com/package/binary) - Unpack multibyte binary values from buffers and streams. Ability to specify endianness and signedness.
- [file-type](https://www.npmjs.com/package/file-type) - Detect the file type of a Buffer/Uint8Array.
- [safe-buffer](https://www.npmjs.com/package/safe-buffer) - Safer `Buffer` API. Uses the [built-in](https://nodejs.org/api/buffer.html) implementation when available.

#### File System

- [fs-extra](https://www.npmjs.com/package/fs-extra) - Adds file system methods that aren't included in the native `fs` module and adds promise support to the `fs` methods.
- [fs-write-stream-atomic](https://www.npmjs.com/package/fs-write-stream-atomic) - Writes to a tmp file and does an atomic `fs.rename` to move it into place when it's done.
- [graceful-fs](https://www.npmjs.com/package/graceful-fs) - Normalize behavior across different platforms and environments, and make filesystem access more resilient to errors.
- [readdirp](https://www.npmjs.com/package/readdirp) - Recursively reads the contents of a directory. Exposes a `stream` api.
- [walkdir](https://www.npmjs.com/package/walkdir) - Find files. Walk a tree of any depth.
- [write-file-atomic](https://www.npmjs.com/package/write-file-atomic) - A `fs.writeFile` extension. makes operations atomic and allows you set ownership of the file.

#### JSON

- [bfj](https://www.npmjs.com/package/bfj) - Asynchronous streaming functions for large JSON data sets.
- [jsonfile](https://www.npmjs.com/package/jsonfile) - Read/write JSON files safely.
- [JSONStream](https://www.npmjs.com/package/JSONStream) - Streaming `JSON.parse` and `JSON.stringify`.

#### Logging

- [draftlog](https://www.npmjs.com/package/draftlog) - Create updatable log lines into the terminal.

#### Parsing

- CSV
  - [csv-write-stream](https://www.npmjs.com/package/csv-write-stream) - A CSV encoder stream that produces properly escaped CSVs.
  - [csv-parser](https://www.npmjs.com/package/csv-parser) - Streaming CSV parser. Converts CSV into JSON at at rate of around 90,000 rows per second.
  - [json2csv](https://www.npmjs.com/package/json2csv) - Converts JSON into csv with column titles and proper line endings.

- Text Extraction
  - [textract](https://www.npmjs.com/package/textract) - Extracts text from a multitude of document types.

#### Pattern Matching

- [globby](https://www.npmjs.com/package/globby) - Match files using the patterns the shell uses.
- [micromatch](https://www.npmjs.com/package/micromatch) - Faster alternative to [minimatch](https://www.npmjs.com/package/minimatch) and [multimatch](https://www.npmjs.com/package/multimatch).

#### Queue

- [async.queue](https://www.npmjs.com/package/async.queue) - [async#queue](https://github.com/async-js/async#async.queue) method as module.
- [run-queue](https://www.npmjs.com/package/run-queue) - Promise based, dynamic priority queue runner, with concurrency limiting.

#### Rate Limiting

- [limiter](https://www.npmjs.com/package/limiter) - Generic rate limiter for node.js.
- [async-throttle](https://www.npmjs.com/package/async-throttle) - Minimal throttling.
- [lodash.debounce](https://www.npmjs.com/package/lodash.debounce) - The [lodash](https://lodash.com/) method `_.debounce`.

#### Retrying

- [async-retry](https://www.npmjs.com/package/async-retry) - Minimal async retrying.
- [retry](https://www.npmjs.com/package/retry) - Abstraction for exponential and custom retry strategies for failed operations.
- [p-retry](https://www.npmjs.com/package/p-retry) - Retry a promise-returning or async function.

#### Scraping / Extracting

- [node-read](https://www.npmjs.com/package/node-read) - Get Readable Content from any page.

#### Streams <a href="https://nodejs.org/api/stream.html" style="font-size:12px;">[docs]</a>

- [concat-stream](https://www.npmjs.com/package/concat-stream) - Collect all the data from a `stream` into a single buffer.
- [duplexer3](https://www.npmjs.com/package/duplexer3) - Like [duplexer2](https://github.com/deoxxa/duplexer2) but using Streams3 without readable-stream dependency.
- [duplexify](https://www.npmjs.com/package/duplexify) - Take a writable and a readable, and turn them into a single [duplex `stream`](https://nodejs.org/api/stream.html#stream_class_stream_duplex).
- [end-of-stream](https://www.npmjs.com/package/end-of-stream) - Waits for `stream` to finish or error and then calls `cb` with `(err)`.
- [event-stream](https://www.npmjs.com/package/event-stream) - Construct pipes of streams of events.
- [flush-write-stream](https://www.npmjs.com/package/flush-write-stream) - Make a custom [writable stream](https://www.npmjs.com/package/mississippi).
- [from2](https://www.npmjs.com/package/from2) - Make a custom [readable stream](https://nodejs.org/docs/latest/api/stream.html#stream_class_stream_readable).
- [is-stream](https://www.npmjs.com/package/is-stream) - Check if something is a `stream`.
- [mute-stream](https://www.npmjs.com/package/mute-stream) - Bytes are silently dropped, rather than being passed through.
- [parallel-transform](https://www.npmjs.com/package/parallel-transform) - Run transforms in parallel without changing the order.
- [pump](https://www.npmjs.com/package/pump) - Pipe streams together and close all of them if one of them closes.
- [pumpify](https://www.npmjs.com/package/pumpify) - Combine an array of streams into a single duplex `stream` using pump and duplexify.
- [stream-each](https://www.npmjs.com/package/stream-each) - Iterate all the data in a `stream`.
- [stream-throttle](https://www.npmjs.com/package/stream-throttle) - Rate limiter for Node.js streams.
- [through2](https://www.npmjs.com/package/through2) - Make a custom [transform stream](https://nodejs.org/docs/latest/api/stream.html#stream_class_stream_transform).
- [through2-concurrent](https://www.npmjs.com/package/through2-concurrent) - Process streams in parallel.

#### CLI Development

- [mri](https://www.npmjs.com/package/mri) - Fast, lightweight alternative to [`minimist`](https://github.com/substack/minimist) and [`yargs-parser`](https://github.com/yargs/yargs-parser).
- [update-notifier](https://www.npmjs.com/package/update-notifier) - Inform users of your package of updates in a non-intrusive way.
- [inquirer](https://www.npmjs.com/package/inquirer) - Collection of common interactive command line user interfaces.

#### Human Language

- [abbrev](https://www.npmjs.com/package/abbrev) - Calculate the set of unique abbreviations for a given set of strings.

## Cryptography

- [crypto](https://nodejs.org/api/crypto.html) - Native `crypto` module. Wrapper for OpenSSL's hash, HMAC, cipher, decipher, sign and verify functions.
- [hasha](https://www.npmjs.com/package/hasha) - Get the hash of a buffer/string/stream/file.
- [unique-slug](https://www.npmjs.com/package/unique-slug) - Generate a unique character string suitible for use in files and URLs.


## HTTP

#### Utilities

- [accepts](https://www.npmjs.com/package/accepts#readme) - Higher level content negotiation based on [negotiator](https://www.npmjs.com/package/negotiator).
- [content-type](https://www.npmjs.com/package/content-type) - Create and parse HTTP Content-Type header according to RFC 7231.
- [get-port](https://www.npmjs.com/package/get-port) - Get an available port.
- [got](https://www.npmjs.com/package/got) - A nicer interface to the built-in [`http`](https://nodejs.org/api/http.html) module.
- [negotiator](https://www.npmjs.com/package/negotiator) - HTTP content negotiator for Node.js.
- [qs](https://www.npmjs.com/package/qs) - Securely parse and stringify querystrings.
- [raw-body](https://www.npmjs.com/package/raw-body) - Parse request bodies.

#### Microservices

- [micro](https://www.npmjs.com/package/micro) - Asynchronous HTTP microservices.
  - [micro-compress](https://github.com/joakimbeng/micro-compress) - Compression middleware.
  - [micro-cors](https://github.com/possibilities/micro-cors) - CORS middleware.
  - [micro-jwt-auth](https://github.com/kandros/micro-jwt-auth) - Json web token(jwt) authorization wrapper.
  - [micro-cookie](https://github.com/zakjholt/micro-cookie) - Cookie parsing.
  - [micro-sentry](https://github.com/tanmulabs/micro-sentry) - Send micro errors to the [Sentry](https://sentry.io) service.

#### Security

- [helmet](https://www.npmjs.com/package/helmet) - Sets sane defaults for various HTTP headers.
- [csurf](https://www.npmjs.com/package/csurf) - [CSRF](https://en.wikipedia.org/wiki/Cross-site_request_forgery) protection middleware.
- [nsp](https://www.npmjs.com/package/nsp) - Detects [known vulnerabilities](https://nodesecurity.io/advisories/) in your projects.

#### WebSockets

- [ws](https://www.npmjs.com/package/ws) - Blazing fast, and thoroughly tested WebSocket client and server implementation.

## Networking

- [airpaste](https://www.npmjs.com/package/airpaste) - A 1-1 network pipe that auto discovers other peers using mdns.
- [bonjour](https://www.npmjs.com/package/bonjour) - Publish services on the local network or discover existing services.
- [castnow](https://www.npmjs.com/package/castnow) - Commandline chromecast player.
- [chromecasts](https://www.npmjs.com/package/chromecasts) - Query local network for Chromecasts and have them play media.
- [multicast-dns](https://www.npmjs.com/package/multicast-dns) - Low level multicast-dns.

## Debugging

- [Chrome DevTools built-in debugger](https://medium.com/@paul_irish/debugging-node-js-nightlies-with-chrome-devtools-7c4a1b95ae27) - Ships with Chrome DevTools. Replaces [node-inspector](https://www.npmjs.com/package/node-inspector).
- [Node/V8 built-in debugger](https://nodejs.org/api/debugger.html) - Out-of-process debugging utility included with Node.
- [debug](https://www.npmjs.com/package/debug) - Small debugging utility.
- [llnode](https://github.com/nodejs/llnode) - Plugin for the [LLDB](http://lldb.llvm.org/) debugger. Advanced, low-level debugger.
- [longjohn](https://www.npmjs.com/package/longjohn) - Produce useful stack traces.

## Testing

#### Unit Testing

- [assert](https://nodejs.org/api/assert.html) - Provides a simple set of assertion tests. A native Node module.
- [ava](https://www.npmjs.com/package/ava) - Minimal and fast. Runs test files in parallel as separate processes. Forces atomic tests.
- [tape](https://www.npmjs.com/package/tape) - Minimal, [tap-producing](https://testanything.org/) test harness.
- [sinon](http://sinonjs.org/) - Test spies, stubs and mocks.

#### Integration Testing

#### Functional Testing

- [supertest](https://www.npmjs.com/package/supertest) - Useful for constructive, descriptive web server tests.

#### Load Testing

- [toxy](https://www.npmjs.com/package/toxy) - HTTP proxy to simulate server failure scenarios and unexpected network conditions.
- [skipfish](https://github.com/spinkham/skipfish)
  - bombards server with valid and invalid requests.
  - improperly closes connections (catches memory leaks).
  - executes common attacks (massive dictionary of common attack vectors).
- [ab](https://httpd.apache.org/docs/2.4/programs/ab.html) - Apache Benchmark.
- [gor](https://github.com/buger/goreplay) -  Captures and replays live HTTP traffic into a test environment.
  - replays actual requests on test server to emulate realistic traffic.
  - exposes layer of errors that can't be easily found via automated and manual testing.
    - concurrency
    - server environment-specific bugs
    - errors due to requests called in a particular order
- [wrk](https://github.com/wg/wrk) - Multithreaded HTTP benchmarking tool.

#### Linting

- [xo](https://www.npmjs.com/package/xo) - Opinionated but configurable ESLint wrapper. Enforces strict and readable code.

#### Code Coverage

- [nyc](https://www.npmjs.com/package/nyc) - [Instanbul](https://istanbul.js.org/docs/tutorials/) driven test coverage.

## Monitoring

- [vtop](https://www.npmjs.com/package/vtop) - A graphical activity monitor for the command line.
