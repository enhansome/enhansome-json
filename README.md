# Awesome JSON with stars

A curated list of awesome JSON libraries and resources.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) ⭐ 498,275 | 🐛 105 | 📅 2026-08-18 list.

[![Links](https://github.com/burningtree/awesome-json/actions/workflows/links.yml/badge.svg)](https://github.com/burningtree/awesome-json/actions/workflows/links.yml) ⭐ 1,563 | 🐛 81 | 📅 2026-06-19

***

* [Awesome JSON](#awesome-json)
  * [Applications](#applications)
  * [Binary Serialization](#binary-serialization)
  * [Browser Extensions](#browser-extensions)
  * [Command-line tools](#command-line-tools)
  * [Databases](#databases)
  * [Datasets](#datasets)
  * [Data modeling](#data-modeling)
  * [Data generation](#data-generation)
  * [Differencing](#differencing)
  * [Editors](#editors)
  * [Format Extensions](#format-extensions)
  * [Frontend components](#frontend-components)
  * [Libraries](#libraries)
  * [Linters](#linters)
  * [Online tools](#online-tools)
  * [Schema Specifications](#schema-specifications)
  * [Services](#services)
  * [Supersets](#supersets)
  * [Related formats](#related-formats)
  * [Resources](#resources)
  * [Templates](#templates)
  * [Testing](#testing)
  * [Text Editor Plugins](#text-editor-plugins)
  * [Transformations](#transformations)
  * [Tutorials](#tutorials)
  * [Queries](#queries)
  * [JSON Schema Frontend components](#json-schema-frontend-components)
  * [JSON Schema Tools](#json-schema-tools)
  * [JSON Schema Resources](#json-schema-resources)
  * [JSON Schema Validators](#json-schema-validators)
  * [Contribute](#contribute)

## Applications

* [Dadroit JSON Viewer](https://dadroit.com) - Very fast JSON Viewer, supporting huge (multi gigabytes) files, JSON log (JSON-Lines and ndjson).

**OS X**

* [JSONExport](https://github.com/Ahmed-Ali/JSONExport) ⭐ 4,806 | 🐛 54 | 🌐 Swift | 📅 2023-10-22 - convert a object to a class of one of the currently supported languages.
* [Visual JSON](https://github.com/youknowone/VisualJSON) ⭐ 304 | 🐛 21 | 🌐 Objective-C | 📅 2016-04-11 - simple JSON pretty-viewer for Mac OS X. (inactive)
* [JSON Design Studio](https://stevespringett.com/free-tools/json-design-studio/) - Professional schema authoring environment.

## Binary Serialization

* [BSON](https://bsonspec.org/) - Binary JSON.
* [MessagePack](https://msgpack.org/) - An extremely efficient object serialization library.
* [UBJSON](https://ubjson.org/) - The universally compatible format specification for binary JSON.
* [CBOR](https://datatracker.ietf.org/doc/html/rfc7049) - Concise Binary Object Representation.
* [PSON](https://github.com/dcodeIO/PSON) ⭐ 463 | 🐛 12 | 🌐 JavaScript | 📅 2017-09-20 - Protocol JSON, super efficient binary serialization format.
* [JSON BinPack](https://www.jsonbinpack.org) - Space-efficient binary JSON serialization format based on JSON Schema.

## Browser Extensions

**Chrome**

* [JSON Formatter](https://chromewebstore.google.com/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa) ([github](https://github.com/callumlocke/json-formatter) ⭐ 4,132 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-26) - Makes JSON easy to read. Open source.
* [JSON Viewer](https://chromewebstore.google.com/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh) ([github](https://github.com/tulios/json-viewer) ⭐ 3,456 | 🐛 203 | 🌐 HTML | 📅 2024-08-20) - It is a Chrome extension for printing JSON and JSONP.
* [JSON Viewer Pro](https://chromewebstore.google.com/detail/json-viewer-pro/eifflpmocdbdmepbjaopkkhbfmdgijcc) ([github](https://github.com/rbrahul/Awesome-JSON-Viewer) ⭐ 582 | 🐛 19 | 🌐 JavaScript | 📅 2026-08-17 - An open source Chrome extension for browsing JSON with syntax highlighting and folding, or as a visual graph.
* [JSON Finder](https://chromewebstore.google.com/detail/json-finder/flhdcaebggmmpnnaljiajhihdfconkbj) ([github](https://github.com/rapee/jsonfinder) ⭐ 41 | 🐛 18 | 🌐 JavaScript | 📅 2022-06-09) - Browse like you do it in Finder.
* [Discoverable JSON](https://chromewebstore.google.com/detail/json-manipulator-json-to/pcakbljjigdafljigcpbmjllkbhlncjg) ([github](https://github.com/noitcudni/discoverable-json) ⭐ 3 | 🐛 0 | 🌐 Clojure | 📅 2021-02-20) - Gron inspired Extension. Convert a JSON document into javascript expressions. Comes with filter, remove, find-and-replace capabilities.

**Firefox**

* [JSONView](https://addons.mozilla.org/en-US/firefox/addon/jsonview/) ([github](https://github.com/bhollis/jsonview) ⭐ 1,712 | 🐛 1 | 🌐 TypeScript | 📅 2026-02-26) - View JSON documents in the browser.

**Safari**

* [JSONView](https://apps.apple.com/us/story/id1377753262?id=com.acrogenesis.jsonview-56Q494QF3L) ([github](https://github.com/acrogenesis/jsonview-safari) ⭐ 292 | 🐛 8 | 🌐 CSS | 📅 2025-06-01) - A port of the JSONView Firefox extension that formats and syntax highlights JSON viewed inside of the browser
* [JSONAce](https://apps.apple.com/us/story/id1377753262?id=com.acrogenesis.jsonace-56Q494QF3LL) ([github](https://github.com/acrogenesis/JSONAce) ⭐ 71 | 🐛 5 | 🌐 JavaScript | 📅 2025-06-01) - Formats & syntax highlights JSON viewed inside of the web browser using the ACE editor.

## Command-line tools

* [jq](https://github.com/jqlang/jq) ⭐ 35,479 | 🐛 472 | 🌐 C | 📅 2026-08-12 - A lightweight and flexible command-line JSON processor.
  * [gojq](https://github.com/itchyny/gojq) ⭐ 3,795 | 🐛 18 | 🌐 Go | 📅 2026-07-20 - Pure Go implementation of jq. A bit faster and more portable.
  * [jaq](https://github.com/01mf02/jaq) ⭐ 3,722 | 🐛 22 | 🌐 Rust | 📅 2026-08-19 - A jq clone focussed on correctness, speed, and simplicity. Written in Rust.
* [fx](https://github.com/antonmedv/fx) ⭐ 20,586 | 🐛 25 | 🌐 Go | 📅 2026-07-28 - A interactive terminal tool.
* [gron](https://github.com/tomnomnom/gron) ⭐ 14,497 | 🐛 50 | 🌐 Go | 📅 2025-05-31 - Convert a JSON file into discrete assignments that are greppable.
* [visidata](https://github.com/saulpw/visidata) ⭐ 9,250 | 🐛 78 | 🌐 Python | 📅 2026-08-15 - A terminal spreadsheet-like tool for interactively exploring data.
* [jc](https://github.com/kellyjonbrazil/jc) ⭐ 8,667 | 🐛 60 | 🌐 Python | 📅 2026-06-18 - Converts the output of many CLI tools, file-types, and common strings into JSON
* [jid](https://github.com/simeji/jid) ⭐ 7,134 | 🐛 10 | 🌐 Go | 📅 2026-08-02 - Incremental Digger. Drill down JSON interactively by using filtering queries like jq.
* [jo](https://github.com/jpmens/jo) ⭐ 4,863 | 🐛 7 | 🌐 C | 📅 2025-06-20 - A small utility to create JSON objects
* [dsq](https://github.com/multiprocessio/dsq) ⭐ 3,865 | 🐛 22 | 🌐 Go | 📅 2023-09-30 - Tool for running SQL queries against JSON, CSV, Excel, Parquet, and more.
* [logdy](https://github.com/logdyhq/logdy-core) ⭐ 2,276 | 🐛 36 | 🌐 Go | 📅 2025-08-25 - jq, tail, less, grep and awk merged together and available in a clean web UI.
* [jsawk](https://github.com/micha/jsawk) ⭐ 1,385 | 🐛 28 | 🌐 Shell | 📅 2021-08-31 - Like awk, but for JSON.
* [oj](https://github.com/ohler55/ojg) ⭐ 953 | 🐛 0 | 🌐 Go | 📅 2026-08-20 - A fast and flexible command line JSON processor.
* [jiq](https://github.com/fiatjaf/jiq) ⚠️ Archived - It's `jid` with `jq`. You can drill down interactively by using `jq` filtering queries.
* [jl](https://github.com/chrisdone/jl) ⚠️ Archived - Functional sed for JSON.
* [jv](https://github.com/maxzender/jv) ⭐ 121 | 🐛 3 | 🌐 Go | 📅 2017-10-30 - jv (for jsonviewer) helps you view your JSON.
* [Parsrs](https://github.com/ShellShoccar-jpn/Parsrs) ⭐ 87 | 🐛 0 | 🌐 Shell | 📅 2026-06-18 - CSV, XML, and data text parsers and generators written in pure POSIX shellscript. Includes `parsrj.sh` and `makrj.sh`.
* [jsoncat](https://github.com/pantuza/jsoncat) ⭐ 26 | 🐛 3 | 🌐 C | 📅 2020-10-05 - Pretty-print Json in terminal with colors and adjusting tabs size.
* [livejq](https://github.com/kunalsin9h/livejq) ⭐ 18 | 🐛 1 | 🌐 Rust | 📅 2024-08-25 - An alternative `jq` implementation in rust for continuous parsing without crashing on invalid JSON
* [json-dotenv](https://github.com/decryptus/json-dotenv) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2023-04-26 - Manipulate and extract envfiles in json format.
* [json-search](https://github.com/cosmo-ray/json-search) ⭐ 4 | 🐛 3 | 🌐 C | 📅 2026-08-10 - A small tool to search for objects/values in json files.
* [jsonskim](https://github.com/rxzzh/jsonskim) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2025-12-29 - Extract structure by collapsing arrays and truncating strings. LLM-ready output.
* [JSONKit](https://github.com/vesper-astrena/jsonkit) - Swiss Army knife: format, validate, query via dot-notation, diff, flatten, convert to CSV, and stats. Zero dependencies, Python 3.10+.
* [json](http://trentm.com/json/) - A "json" command for massaging JSON on your Unix command line.
* [jshon](https://web.archive.org/web/20240206155217/http://kmkeen.com/jshon/) - A parser designed for maximum convenience within the shell.
* [jarg](http://jdp.github.io/jarg/) - Shorthand JSON and form encoding syntax in the shell.

## Databases

* [JSON Server](https://github.com/typicode/json-server) ⭐ 75,680 | 🐛 720 | 🌐 JavaScript | 📅 2026-03-23 - Get a full fake REST API with zero coding in less than 30 seconds.
* [RxDB](https://github.com/pubkey/rxdb) ⭐ 23,355 | 🐛 14 | 🌐 TypeScript | 📅 2026-08-21 - Event-driven JSON-Database with JSON-Schema, mango-Query and CouchDB-sync. (Javascript)
* [lowdb](https://github.com/typicode/lowdb) ⭐ 22,572 | 🐛 16 | 🌐 JavaScript | 📅 2026-03-27 - Flat file database built on lodash API. (Javascript)
* [Kinto](https://github.com/Kinto/kinto) ⭐ 4,416 | 🐛 94 | 🌐 Python | 📅 2026-08-14 - A lightweight JSON storage service with synchronisation and sharing abilities.
* [Lawnchair](https://github.com/brianleroux/lawnchair) ⭐ 2,126 | 🐛 86 | 🌐 JavaScript | 📅 2020-05-17 - A lightweight clientside document store. (Javascript)
* [EJDB](https://github.com/Softmotions/ejdb) ⭐ 1,478 | 🐛 35 | 🌐 C | 📅 2026-08-19 - Embedded JSON Database engine published under MIT license. (C)
* [JSONlite](https://github.com/nodesocket/jsonlite) ⭐ 843 | 🐛 2 | 🌐 Shell | 📅 2025-03-03 - A simple, self-contained, serverless, zero-configuration, json document store. (Bash)
* [JSON ODM](https://github.com/konsultaner/jsonOdm) ⭐ 100 | 🐛 1 | 🌐 JavaScript | 📅 2023-03-08 - Object document mapper for JavaScript to use on the server or in the browser. (Javascript)
* [MongoDB](https://www.mongodb.com/) - an open-source document database, and the leading NoSQL database.
* [RethinkDB](https://rethinkdb.com/) - An open-source distributed document database with a pleasant and powerful query language.
* [CouchDB](https://couchdb.apache.org/) - Seamless multi-master sync, that scales from Big Data to Mobile, with an Intuitive HTTP/JSON API and designed for Reliability.

## Datasets

* [country.io](http://country.io/data/) - Various country related datasets, as JSON inc currency, country codes, names and more
* [countries](https://github.com/mledoze/countries) ⭐ 6,254 | 🐛 17 | 🌐 PHP | 📅 2026-07-20 - World countries.
* [MTG JSON](https://mtgjson.com/) - Up to date Magic the Gathering card data.
* [Heartstone JSON](https://hearthstonejson.com/) - Up to date Hearthstone card data.
* [getCountries()](https://peric.github.io/GetCountries/) - Generator for custom Countries data.

## Data modeling

* [JSONModel](https://github.com/jsonmodel/jsonmodel) ⭐ 6,808 | 🐛 34 | 🌐 Objective-C | 📅 2021-11-06 - Magical Data Modelling Framework. (Objective-C)

## Data generation

* [dyson](https://github.com/webpro/dyson) ⚠️ Archived - Server for dynamic, fake JSON. (node.js)
* [jsonymize](https://github.com/cameronhunter/jsonymize) ⚠️ Archived - Reads data from standard input, anonymizes, then writes to standard output.

## Differencing

* [jsondiffpatch](https://github.com/benjamine/jsondiffpatch) ⭐ 5,335 | 🐛 55 | 🌐 TypeScript | 📅 2026-05-14 - Diff & patch for JavaScript objects. (Javascript)
* [JSON-Patch](https://github.com/Starcounter-Jack/JSON-Patch) ⭐ 1,980 | 🐛 83 | 🌐 JavaScript | 📅 2025-10-23 - Lean and mean Javascript implementation of the JSON-Patch standard (RFC 6902). (Javascript)
* [jiff](https://github.com/cujojs/jiff) ⭐ 641 | 🐛 16 | 🌐 JavaScript | 📅 2024-08-11 - JSON Patch and diff based on rfc6902. (Javascript)
* [dffptch](https://github.com/paldepind/dffptch) ⭐ 171 | 🐛 1 | 🌐 JavaScript | 📅 2017-01-11 - A micro library for diffing and patching using a compact diff format. (Javascript)
* [json-patch-php](https://github.com/mikemccabe/json-patch-php) ⭐ 112 | 🐛 13 | 🌐 PHP | 📅 2019-02-26 - implementation of JSON-patch (IETF RFC 6902) (PHP)
* [JSONPatch](https://jsonpatch.com/) - A format for describing changes to a document.

## Editors

* [FrontAid CMS](https://frontaid.io/) - Content Management System that supports arbitrary data model structures.
* [JSON table editor](https://jsontable.app/) - Display JSON array as table, provides search, filtering and edition features. It supports large files of multiple gigabytes. (Rust).
* [JSONEdit](http://mb21.github.io/JSONedit/) - User friendly, visual editor built as an AngularJS directive.
* [JSON Crack](https://jsoncrack.com/) - Display your JSON as a graph

## Format Extensions

* [NDJSON](https://github.com/ndjson/ndjson-spec) ⭐ 843 | 🐛 17 | 📅 2022-10-20 (Newline delimited JSON) - a standard for delimiting JSON in stream protocols.
* [JSON6](https://github.com/d3x0r/json6) ⭐ 241 | 🐛 7 | 🌐 JavaScript | 📅 2021-10-18 - JSON for Humans (ES6).
* [Sequence JSON](https://github.com/soundio/music-json/) ⭐ 141 | 🐛 5 | 🌐 JavaScript | 📅 2026-07-29 - A proposal for a standard way of creating music sequence data in JSON.
* [JSON-stat](https://github.com/jsonstat/jsonstat) ⭐ 26 | 🐛 2 | 📅 2021-09-08 - Simple lightweight format for data dissemination.
* [J<sub>ack</sub>SON: JSON secret keeper](https://github.com/rosehgal/jackson) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2020-12-29 - JSONic way of storing secrets in config file.
* [GeoJSON](https://geojson.org/) - A geospatial data interchange format.
* [JSON-LD](https://json-ld.org/) - A lightweight Linked Data format.
* [JSON-RPC](https://www.jsonrpc.org/) - A stateless, light-weight remote procedure call (RPC) protocol.
* [JSONP](https://en.wikipedia.org/wiki/JSONP) - Safer cross-domain Ajax with JSON-P/JSONP.
* [JsonML](http://www.jsonml.org/) - A compact format for transporting XML-based markup as JSON which allows it to be losslessly converted back to its original form.
* [JSON5](https://json5.org/) - a extension that aims to make it easier for humans to write and maintain by hand.
* [JSON 1.1/JSONX](https://json-next.github.io/) - An evolved version 1.1 with format extension for humans incl. comments, unquoted and multi-line strings, optional and trailing commas and more.
* [JSON Resume](https://jsonresume.org/) - The open source initiative to create standard for resumes.
* [JSON Web Tokens](https://jwt.io/) - A compact URL-safe means of representing claims to be transferred between two parties.
* [JSON API](https://jsonapi.org/) - A standard for building APIs.
* [JSON Activity Streams](https://activitystrea.ms/) - A format for syndicating social activities around the web.
* [/contribute.json](https://www.contributejson.org/) - Making open source contribution information easier to access, across projects.
* [survey.js](https://surveyjs.io/form-library) - JSON based survey library.
* [JSON Meta Application Protocol (JMAP)](https://jmap.io/) - A protocol for synchronising JSON-based data objects efficiently, with support for push and out-of-band binary data upload/download.

## Frontend components

* [ngx-formly](https://github.com/ngx-formly/ngx-formly) ⭐ 2,965 | 🐛 36 | 🌐 TypeScript | 📅 2026-08-17 - JSON powered / Dynamic forms for Angular

* [Dynatable.js](https://github.com/alfajango/jquery-dynatable) ⭐ 2,751 | 🐛 228 | 🌐 JavaScript | 📅 2022-02-25 - A funner, semantic, HTML5+JSON, interactive table plugin. (jQuery)

* [JSON editor jQuery plugin](https://github.com/DavidDurman/FlexiJsonEditor) ⭐ 564 | 🐛 19 | 🌐 JavaScript | 📅 2019-02-05 - component for you web apps/pages. (jQuery)

* [@textea/json-viewer](https://github.com/TexteaInc/json-viewer) ⭐ 533 | 🐛 27 | 🌐 TypeScript | 📅 2025-07-04 - A React component for JSON viewer. (React)

* [JSON Formatter](https://github.com/mohsen1/json-formatter) ⭐ 370 | 🐛 21 | 🌐 JavaScript | 📅 2020-10-17 - Angular directive for collapsible JSON in HTML. (AngularJS)

* [jqTree](http://mbraak.github.io/jqTree/) - Widget for displaying a tree structure in html. (jQuery)

* [jsTree](https://www.jstree.com/docs/json/) - jquery plugin, that provides interactive trees. (jQuery)

* [react-jsonschema-form](https://rjsf-team.github.io/react-jsonschema-form/) - A React component for building Web forms from JSON Schema. (React)

* [SmarkForm](https://smarkform.bitifet.net) - Enhance HTML forms to import/export any possible data, including arrays and subforms to any depth.

## Libraries

**C**

* [Jansson](https://github.com/akheron/jansson) ⭐ 3,357 | 🐛 127 | 🌐 C | 📅 2026-07-09 - A C library for encoding, decoding and manipulating data.
* [json-build](https://github.com/lcsmuller/json-build) ⭐ 53 | 🐛 0 | 🌐 C | 📅 2025-04-12 - A minimalistic serializer in C. It can be easily integrated into the resource-limited projects or embedded systems.
* [ojc](https://github.com/ohler55/ojc) ⭐ 38 | 🐛 1 | 🌐 C | 📅 2024-04-24 - A fast JSON parser.
* [codables](https://codableslib.com/) - Declarative, type-rich (de)serializer able to handle almost any data type.
* [jsmn](https://zserge.com/jsmn.html) - A minimalistic parser in C. It can be easily integrated into the resource-limited projects or embedded systems.

**C++**

* [Nlohmann JSON](https://github.com/nlohmann/json) ⭐ 50,413 | 🐛 98 | 🌐 C++ | 📅 2026-08-21 - A C++11 header-only class.
* [simdjson](https://github.com/simdjson/simdjson) ⭐ 24,164 | 🐛 134 | 🌐 C++ | 📅 2026-08-20 - Parsing gigabytes of JSON per second.
* [RapidJSON](https://github.com/Tencent/rapidjson) ⭐ 15,114 | 🐛 790 | 🌐 C++ | 📅 2025-02-05 - A fast JSON parser/generator for C++ with both SAX/DOM style API
* [ArduinoJson](https://github.com/bblanchon/ArduinoJson) ⭐ 7,203 | 🐛 17 | 🌐 C++ | 📅 2026-08-15 - An efficient library for embedded systems.
* [json11](https://github.com/dropbox/json11) ⚠️ Archived - A tiny library for C++11.
* [JSON++](https://github.com/tunnuz/json) ⭐ 41 | 🐛 6 | 🌐 C++ | 📅 2016-06-15 - A self contained Flex/Bison parser for C++11.
* [qjson](https://github.com/qinyonghang/json) ⭐ 7 | 🐛 0 | 🌐 C++ | 📅 2025-09-05 - A fast library for C++17 that is header-only.

**Clojure**

* [data.json](https://github.com/clojure/data.json) ⭐ 578 | 🐛 2 | 🌐 Clojure | 📅 2026-01-02 - parser/generator to/from Clojure data structures.

**Fortran**

* [JSON-Fortran](https://github.com/jacobwilliams/json-fortran) ⭐ 381 | 🐛 25 | 🌐 Fortran | 📅 2026-06-11 - A Fortran library for writing, reading, and manipulating JSON files and data structures.

**Go**

* [ojg](https://github.com/ohler55/ojg) ⭐ 953 | 🐛 0 | 🌐 Go | 📅 2026-08-20 - A collection of high performance JSON processing and generating tool.

**Haskell**

* [aeson-qq](https://github.com/sol/aeson-qq) ⭐ 79 | 🐛 3 | 🌐 Haskell | 📅 2023-05-21 - JSON quasiquoter for Haskell.
* [json-schema](http://hackage.haskell.org/package/json-schema) - JSON Schema library for Haskell
* [hjsonschema](http://hackage.haskell.org/package/hjsonschema) - JSON Schema Draft 4 library for Haskell

**Java**

* [Fast JSON Processor](https://github.com/alibaba/fastjson) ⚠️ Archived
* [Gson](https://github.com/google/gson) ⭐ 24,227 | 🐛 340 | 🌐 Java | 📅 2026-08-14 - A Java library to convert JSON to Java objects and vice-versa.
* [moshi](https://github.com/square/moshi) ⭐ 10,154 | 🐛 112 | 🌐 Kotlin | 📅 2026-08-19 - A modern JSON library for Android and Java.
* [Jackson](https://github.com/FasterXML/jackson) ⭐ 9,801 | 🐛 0 | 📅 2026-07-17 - A multi-purpose Java library for processing JSON data format.
* [JSON-java](https://github.com/stleary/JSON-java) ⭐ 4,717 | 🐛 23 | 🌐 Java | 📅 2026-08-14 - A reference implementation.
* [dsl-json](https://github.com/ngs-doo/dsl-json) ⭐ 1,070 | 🐛 48 | 🌐 Java | 📅 2026-06-29 - A very fast streaming JSON library. Operates on byte arrays.
* [mjson](https://github.com/bolerio/mjson) ⭐ 93 | 🐛 19 | 🌐 Java | 📅 2025-06-28 - Lean JSON Library for Java, with a compact, elegant API.
* [essential-json](https://github.com/arkanovicz/essential-json) ⭐ 25 | 🐛 0 | 🌐 Java | 📅 2022-08-30 - A lightweight Java library for serialization, parsing and manipulation with a clean and precise API.

**Javascript**

* [JSON-js](https://github.com/douglascrockford/JSON-js) ⭐ 8,718 | 🐛 0 | 🌐 JavaScript | 📅 2023-05-10 - JSON in JavaScript.
* [oboe.js](https://github.com/jimhigson/oboe.js) ⭐ 4,817 | 🐛 119 | 🌐 JavaScript | 📅 2025-11-17 - A streaming approach, speeds up web applications by providing parsed objects before the response completes.
* [JsonHilo](https://github.com/xtao-org/jsonhilo) ⭐ 45 | 🐛 4 | 🌐 JavaScript | 📅 2025-08-24 - Minimal lossless parse event streaming, akin to SAX.
* [JSON 3](https://bestiejs.github.io/json3/) - A modern implementation.
* [FracturedJsonJs](https://www.npmjs.com/package/fracturedjsonjs) - A JSON formatter that produces human-readable but fairly compact output.

**Objective-C**

* [JSONKit](https://github.com/johnezang/JSONKit) ⭐ 6,176 | 🐛 103 | 🌐 Objective-C | 📅 2020-11-22 - Objective-C library.
* [SBJson](https://github.com/SBJson/SBJson) ⭐ 3,717 | 🐛 1 | 🌐 Objective-C | 📅 2026-05-18 - Parse one or more chunks of data.

**Perl**

* [JSON::Tiny](https://github.com/daoswald/JSON-Tiny) ⭐ 10 | 🐛 0 | 🌐 Perl | 📅 2017-11-12 - Perl module for encoding and decoding JSON in a minimalistic way.

**PL/SQL**

* [PL/JSON](https://github.com/pljson/pljson) ⭐ 460 | 🐛 7 | 🌐 PLSQL | 📅 2024-06-26 - A generic JSON object written in PL/SQL.

**PHP**

* [Webmozart JSON](https://github.com/webmozart/json) ⭐ 352 | 🐛 12 | 🌐 PHP | 📅 2021-03-06 - A robust decoder/encoder with support for schema validation.
* [TOON PHP Lite](https://github.com/manojrammurthy/toon-php-lite) ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2025-11-19 - Lightweight TOON encoder/decoder for human-readable, LLM-friendly structured data. (PHP).

**Python**

* [simplejson](https://github.com/simplejson/simplejson) ⭐ 1,711 | 🐛 13 | 🌐 Python | 📅 2026-08-06 - A simple, fast, extensible encoder/decoder
* [jsonpickle](http://jsonpickle.github.io/) - Library for serializing any arbitrary object graph.
* [metamagic.json](https://pypi.org/project/metamagic.json/) - An ultra-fast Python 3 implementation of a JSON encoder.

**Ruby**

* [oj](https://github.com/ohler55/oj) ⭐ 3,225 | 🐛 14 | 🌐 C | 📅 2026-08-13 - A fast JSON parser and Object marshaller as a Ruby gem.
* [MultiJSON](https://github.com/intridea/multi_json) ⭐ 765 | 🐛 2 | 🌐 Ruby | 📅 2025-06-24 - A generic swappable back-end for JSON handling.

**React**

* [json2react](https://github.com/txgruppi/json2react) ⭐ 173 | 🐛 2 | 🌐 JavaScript | 📅 2022-12-30 - Use JSON to create React Stateless Components.

**.NET**

* [jsonfx](https://github.com/jsonfx/jsonfx) ⭐ 378 | 🐛 20 | 🌐 C# | 📅 2016-12-24 - serialization framework for .NET.
* [jsonapi-consumer](https://github.com/OKTAYKIR/jsonapi-consumer) ⭐ 7 | 🐛 1 | 🌐 C# | 📅 2022-12-07 - Client framework for consuming JSONAPI based APIs on the [JSON API standard](https://jsonapi.org).

**Scala**

* [circe](https://github.com/circe/circe) ⭐ 2,542 | 🐛 127 | 🌐 Scala | 📅 2026-07-23 - Yet another JSON library for Scala.
* [spray-json](https://github.com/spray/spray-json) ⭐ 972 | 🐛 100 | 🌐 Scala | 📅 2024-01-10 - A lightweight, clean and simple implementation in Scala.
* [jsoniter-scala](https://github.com/plokhotnyuk/jsoniter-scala) ⭐ 819 | 🐛 98 | 🌐 Scala | 📅 2026-08-20 - Scala macros for compile-time generation of ultra-fast JSON codecs.
* [scala-jsonapi](https://github.com/scala-jsonapi/scala-jsonapi) ⭐ 108 | 🐛 13 | 🌐 Scala | 📅 2018-12-28 - Support library for integrating the JSON:API spec with Play, Spray and/or Circe backends.

**Shell**

* [jshn](https://openwrt.org/docs/guide-developer/jshn) - JSON parsing and generation library in for shell scripts (Ash/Bash)

**Swift**

* [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) ⭐ 22,948 | 🐛 139 | 🌐 Swift | 📅 2026-08-18 - The better way to deal with data in Swift.

* [yyjson](https://github.com/ibireme/yyjson) ⭐ 3,843 | 🐛 39 | 🌐 C | 📅 2026-08-19 - High performance parser and serializer in C.

## Linters

* [jsonlint](https://github.com/zaach/jsonlint) ⭐ 1,992 | 🐛 80 | 🌐 JavaScript | 📅 2022-07-12 - Parser and validator with a CLI. (Javascript)
* [JSON Lint](https://github.com/Seldaek/jsonlint) ⭐ 1,325 | 🐛 1 | 🌐 PHP | 📅 2026-08-01 - PHP linter. (PHP)

## Online tools

* [Dadroit V Web](https://dadroit.com/vweb/) - In-browser viewer for large files with tree view, RegEx search, and URL loading with auth. Fully client-side.
* [DataFormatter Pro](https://dataformatterpro.com/) - Browser-based formatter, validator, diff, and converter with a tree view.
* [JSON Blob](https://jsonblob.com/) - An online tool to view, edit, format, and share data. Also has an API for making requests against stored blobs.
* [JSON Viewer Tool](https://jsonviewertool.com/) - Online tool to view, format, validate, minify, and convert data in the browser.
* [JSONLint](https://jsonlint.com/) - The JSON Validator.
* [JSONCompare](https://jsoncompare.com/) - The Advanced Version of the JSON Linter.
* [JSONMaster](https://jsonmaster.com/) - Free online validator, formatter, minifier and viewer.
* [JSONMate](https://www.jsonmate.com/) - JSON editor, inspector and beautifier.
* [JSON Editor online](https://jsoneditoronline.org/) - A web-based tool to view, edit and format.
* [Collapsible JSON Formatter](http://www.bodurov.com/JsonFormatter/) - Formatter and Colorer of Raw Code.
* [JSON Formatter and Validator](https://jsonformatter.curiousconcept.com/) - Formatter to help with debugging.
* [JSON Generator](https://json-generator.com/) - Tool for generating random data.
* [FakeJSON](https://fakejson.com/) - Web API to quickly generate fake data for your application.
* [JSON to CSV](https://konklone.io/json/) - A free, in-browser JSON to CSV converter.
* [CSV to JSON](https://alef.website/tools/csv-to-json) - Easy, privacy-friendly and offline-first online csv to json converter
* [json2csharp](https://json2csharp.com/) - Generate c# classes from a json string or url.
* [JSON Utils](http://jsonutils.com/) - Site for generating C#, VB.Net, and Javascript classes from JSON.
* [geojson.io](https://geojson.io/) - Simply edit GeoJSON map data.
* [jq play](https://jqplay.org/) - A playground for jq.
* [json2yaml](https://www.json2yaml.com/) - Convert JSON to YAML online.
* [JSON Selector Generator](http://jsonselector.com/) - A simple GUI for generating the selectors to access.
* [JSON.fr](https://www.json.fr/) - Fully client-side validator and formatter.
* [JSONtapose](https://www.jsontapose.com/) - Intuitive, beautiful and secure client-side comparison and visualization tool.
* [jsontosdk](https://jsontosdk.vercel.app) - Paste a data sample to get typed TypeScript interfaces and a Zod schema with LLM-named types. No signup.
* [ObjGen](https://www.objgen.com/json) - Online live JSON generator.
* [JSONPlaceholder](https://jsonplaceholder.typicode.com/) - Fake Online REST API for Testing and Prototyping.
* [Extends Class](https://extendsclass.com/json-diff.html) - Diff tool to compare two files.
* [JSON Schema Validate API](https://assertible.com/json-schema-validation) - A simple and free JSON Schema Validation API.
* [JSONPerf](https://jsonperf.com) - A Visual, Unbiased and Up-to-Date JSON Performance Benchmark.
* [FracturedJson](https://j-brooke.github.io/FracturedJson/) - Formatter that produces human-readable but fairly compact output.
* [Softwium](https://softwium.com/fake-api/) - Fake and dummy REST API for testing.
* [JSONing](https://jsoning.com/) - A toolset including a formatter, comparer, JSONPath tester, patch generator, and data generator.

## Schema Specifications

* [Kwalify](https://github.com/kvs/kwalify) ⚠️ Archived - A parser, schema validator, and data binding tool
* [JSON Model](https://github.com/clairey-zx81/json-model) ⭐ 8 | 🐛 3 | 🌐 C | 📅 2026-08-20 - A lightweight featureful DSL for data modeling.
* [JSON Schema](https://json-schema.org/) - a JSON based format for defining the structure of JSON data.
* [Itemscript](https://code.google.com/archive/p/itemscript/) - Language for validating and specifying values.
* [Rx](https://rx.codesimply.com/) - Simple, Extensible Schemata.

## Services

* [Exchange Rate API](https://www.exchangerate-api.com) - A simple and free API for currency exchange rate data.
* [ipinfo.io](https://ipinfo.io) - JSON IP and GeoIP REST API.
* [JSONProxy](https://github.com/afeld/jsonp) ⚠️ Archived - Simple HTTP proxy that enables cross-domain requests to any JSON API.
* [Telize](https://www.telize.com/) - JSON IP and GeoIP REST API.
* [jsonpad](https://jsonpad.io/) - a simple JSON storage platform.

## Supersets

* [TOML](https://github.com/toml-lang/toml) ⭐ 20,580 | 🐛 16 | 📅 2026-07-03 - A minimal configuration file format that's easy to read due to obvious semantics.
* [HOCON](https://github.com/lightbend/config/blob/master/HOCON.md) ⭐ 6,312 | 🐛 243 | 🌐 Java | 📅 2026-07-01 - Human-Optimized Config Object Notation.
* [HCL](https://github.com/hashicorp/hcl) ⭐ 5,797 | 🐛 237 | 🌐 Go | 📅 2026-08-20 - A structured configuration language that is both human and machine friendly.
* [HanSON](https://github.com/timjansen/hanson) ⭐ 157 | 🐛 5 | 🌐 JavaScript | 📅 2023-02-01 - JSON for Humans - with unquoted identifiers, multi-line strings and comments.
* [μson](https://github.com/burningtree/uson) ⭐ 80 | 🐛 12 | 🌐 JavaScript | 📅 2022-12-30 (uson) - a shorthand for JSON.
* [ASON](https://github.com/sadmac7000/libason) ⭐ 2 | 🐛 1 | 🌐 C | 📅 2015-03-07 - A semantically complete superset of JSON (draft).
* [YAML](https://yaml.org) - A human friendly data serialization standard for all programming languages.

## Tutorials

* [Introducing JSON](http://json.org/)
* [JSON Tutorial](https://www.w3resource.com/JSON/introduction.php) - An introductory tutorial on JavaScript Object Notation (JSON).
* [JSON - Rosetta Code](https://rosettacode.org/wiki/JSON) - Basic operations in different languages (57 languages in this moment).
* [What is JSON and how to use it](https://ilovecoding.org/lessons/json-what-is-json-and-how-to-use-it) - Video tutorial for beginners.
* [jq Primer: Munging JSON Data](https://andrew.gibiansky.com/) - How jq can be used to process JSON files just as effectively as traditional Unix tools.

## Related formats

* [CSON](https://github.com/bevry/cson) ⭐ 1,341 | 🐛 4 | 🌐 CoffeeScript | 📅 2026-08-11 - CoffeeScript-Object-Notation. JSON for CoffeeScript objects.
* [MSON](https://github.com/apiaryio/mson) ⚠️ Archived - Markdown syntax compatible with describing JSON and JSON Schema.
* [AXON](https://github.com/intellimath/pyaxon) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2016-08-06 - A simple text based format for interchanging of objects, documents and data. It tries to combine the best of JSON, XML and YAML.
* [ArchieML](http://archieml.org/) - Structured text format optimized for human writability.

## Resources

* [Awesome jq](https://github.com/fiatjaf/awesome-jq) ⭐ 975 | 🐛 5 | 📅 2026-08-17 - A curated list of awesome jq tools and resources.
* [Type-o-rama](https://github.com/stereobooster/type-o-rama) ⭐ 247 | 🐛 1 | 📅 2022-11-14 - JS type systems interportability, comparison of different JS type systems and conversion between them.

## Templates

* [Jsonnet](https://jsonnet.org/) - A domain specific configuration language that helps you define JSON data.
* [rabl](https://github.com/nesquena/rabl) ⭐ 3,633 | 🐛 122 | 🌐 Ruby | 📅 2026-03-18 - General ruby templating with json, bson, xml, plist and msgpack support. (Ruby)
* [json2html](http://json2html.com/) - HTML templating library with wrappers for both jQuery and Node.js. (Javascript)

## Testing

* [JSON Parsing Test Suite](https://github.com/nst/JSONTestSuite) ⭐ 1,157 | 🐛 53 | 🌐 C++ | 📅 2024-11-22 - A very complete test suite and validation framework.
* [JSONassert](https://github.com/skyscreamer/JSONassert) ⭐ 1,056 | 🐛 94 | 🌐 Java | 📅 2024-07-28 - Write JSON unit tests in less code. Great for testing REST interfaces. (Java)
* [JsonUnit](https://github.com/lukas-krecan/JsonUnit) ⭐ 1,003 | 🐛 14 | 🌐 Java | 📅 2026-08-21 - A library that simplifies JSON comparison in unit tests. It's strongly inspired by XmlUnit.
* [JSON Test](http://www.jsontest.com/) - Testing platform for services utilizing JavaScript Object Notation (JSON).

## Text Editor Plugins

**Emacs**

* [JSON Reformat](https://github.com/gongo/json-reformat) ⭐ 175 | 🐛 0 | 🌐 Emacs Lisp | 📅 2022-09-06 - Reformat tool.

**Vim**

* [vim-json](https://github.com/elzr/vim-json) ⭐ 1,230 | 🐛 45 | 🌐 Vim script | 📅 2024-05-19 - A better JSON for Vim: distinct highlighting of keywords vs values, JSON-specific (non-JS) warnings, quote concealing. Pathogen-friendly.

**Visual Studio Code**

**Neovim**

* [nvim-jqx](https://github.com/gennaro-tedesco/nvim-jqx) ⭐ 339 | 🐛 2 | 🌐 Lua | 📅 2024-05-31 - Browse and query json files in neovim from the quickfix window. (Lua)

## Transformations

* [normalizr](https://github.com/paularmstrong/normalizr) ⚠️ Archived - Normalizes nested JSON according to a schema. (Javascript)
* [fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser) ⭐ 3,131 | 🐛 13 | 🌐 JavaScript | 📅 2026-08-19 - Fast XML to JSON and vice versa javascript/JSON conversion.
* [JsonMapper](https://github.com/cweiske/jsonmapper) ⭐ 1,573 | 🐛 2 | 🌐 PHP | 📅 2026-06-30 - Map nested structures onto PHP classes (PHP)
* [x2js](https://github.com/abdolence/x2js) ⭐ 1,004 | 🐛 57 | 🌐 JavaScript | 📅 2022-01-24 - XML to JSON and vice versa javascript conversion functions. (Javascript)
* [osmtogeojson](https://github.com/tyrasd/osmtogeojson) ⭐ 750 | 🐛 59 | 🌐 JavaScript | 📅 2026-04-23 - Converts OSM data to GeoJSON. (Javascript)
* [JSONC](https://github.com/tcorral/JSONC) ⭐ 652 | 🐛 22 | 🌐 JavaScript | 📅 2018-12-11 - JSON compressor and decompressor. (Javascript)
* [CircularJSON](https://github.com/WebReflection/circular-json) ⚠️ Archived - JSON does not handle circular references. Now it does.
* [json2json](https://github.com/joelvh/json2json) ⭐ 191 | 🐛 5 | 🌐 CoffeeScript | 📅 2021-07-26 - Transform (reformat) structures from one to another. (Javascript)
* [trans](https://github.com/gabesoft/trans) ⭐ 178 | 🐛 1 | 🌐 JavaScript | 📅 2015-12-21 - The ultimate object transformer. (Javascript)
* [SassyJSON](https://github.com/KittyGiraudel/SassyJSON) ⚠️ Archived - Sass-powered API. (Sass)
* [JSON-populate](https://github.com/eiriklv/json-populate) ⭐ 160 | 🐛 0 | 🌐 JavaScript | 📅 2022-09-02 - Tool for populating JSON data with infinitely recursive circular references. Sort of like Falcor, but for plain JSON.
* [json-transforms](https://github.com/ColinEberhardt/json-transforms) ⭐ 146 | 🐛 8 | 🌐 JavaScript | 📅 2024-08-27 - A recursive, pattern-matching, approach to transforming JSON structures.
* [Sawmill](https://github.com/logzio/sawmill) ⭐ 123 | 🐛 16 | 🌐 Java | 📅 2026-07-22 - JSON transformation library (Java)
* [nimnjs](https://github.com/NaturalIntelligence/nimnjs) ⭐ 46 | 🐛 0 | 🌐 JavaScript | 📅 2023-10-14 - JSON to nimn bidirectional converter.
* [fanci](https://github.com/liip/fanci) ⭐ 29 | 🐛 1 | 🌐 JavaScript | 📅 2017-07-06 - Extract, rename and transform JSON based on a template. (node.js)
* [jsontl](https://github.com/DoublePrecisionSoftware/jsontl) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2015-03-30 - allow transformation using a JSON-based transformation language. (node.js)
* [json-sharp](https://github.com/globocom/json-sharp) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2017-06-28 - Javascript tool to process operations on pure JSON objects. (Javascript)
* [stylops](https://github.com/cruel-intentions/stylops) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-12 - CSS subset to JSON conversion. (node.js)
* [json.human.js](http://marianoguerra.github.io/json.human.js/) - A small library to convert a JSON object into a human readable HTML representation that is easy to style for different purposes.
* [deepjson](https://www.npmjs.com/package/deepjson/) - A better way to load big json config files. (node.js)

## Queries

* [dasel](https://github.com/tomwright/dasel) ⭐ 8,020 | 🐛 25 | 🌐 Go | 📅 2026-08-16 - Query and update data structures using selectors from the command line. Comparable to [jq](https://github.com/jqlang/jq) ⭐ 35,479 | 🐛 472 | 🌐 C | 📅 2026-08-12 / [yq](https://github.com/kislyuk/yq) ⭐ 2,969 | 🐛 23 | 🌐 Python | 📅 2026-07-11 but supports JSON, YAML, TOML and XML with zero runtime dependencies.
* [JSONSelect](https://github.com/lloyd/JSONSelect) ⭐ 1,588 | 🐛 46 | 🌐 JavaScript | 📅 2021-08-31 - CSS-like selectors. (Javascript)
* [JSON Mask](https://github.com/nemtsov/json-mask) ⭐ 870 | 🐛 4 | 🌐 JavaScript | 📅 2026-01-18 - Tiny language and engine for selecting specific parts of a JS object, hiding the rest. (Javascript)
* [searchjs](https://github.com/deitch/searchjs) ⭐ 309 | 🐛 10 | 🌐 JavaScript | 📅 2025-02-19 - A library for filtering based on a json SQL-like language.
* [json-rel](https://github.com/slurmulon/json-where) ⭐ 16 | 🐛 6 | 🌐 JavaScript | 📅 2022-12-05 - Transparent references in JSON.
* [JMESPath](https://jmespath.org/) - A query language for JSON.
* [JSONiq](https://www.jsoniq.org/) - The JSON Query Language.
* [ObjectPath](https://objectpath.org/) - The agile query language for semi-structured data. (Python)
* [DefiantJS](https://www.defiantjs.com/) - Lightning-fast searches using XPath expressions, and transform using XSL. (Javascript)
* [JSONPath](https://goessner.net/articles/JsonPath/) - XPath implementation. (Javascript/PHP)
* [JSONata](https://jsonata.org/) - Query and transformation language used in Node-RED, supports function expressions.

## JSON Schema Frontend components

* [JSON Editor](https://github.com/jdorn/json-editor) ⭐ 5,818 | 🐛 455 | 🌐 JavaScript | 📅 2018-04-18 - JSON Schema Based Editor. (jQuery)
* [angular-schema-form](https://github.com/json-schema-form/angular-schema-form) ⭐ 2,454 | 🐛 128 | 🌐 JavaScript | 📅 2023-02-20 - Generate forms. (AngularJS)
* [JSON Schema View](https://github.com/mohsen1/json-schema-view) ⭐ 50 | 🐛 2 | 🌐 JavaScript | 📅 2017-01-13 - An AngularJS directive for rendering JSON Schema in HTML (AngularJS)
* [Angular JSON Schema Form](https://github.com/mohsen1/angular-json-schema-form) ⭐ 30 | 🐛 6 | 🌐 JavaScript | 📅 2016-07-12 - Angular directive for making forms out of JSON Schema. (AngularJS)
* [AlpacaJS](http://www.alpacajs.org) - Generates JSON Schema driven forms on top of Bootstrap, jQuery Mobile, jQuery UI and HTML (jQuery)

## JSON Schema Tools

* [jsonschema2pojo](https://github.com/joelittlejohn/jsonschema2pojo) ⭐ 6,380 | 🐛 251 | 🌐 Java | 📅 2026-05-02 - Generates Java types and annotates those types for data-binding with Jackson 1.x or 2.x, Gson, etc.
* [JSON Schema + Faker](https://github.com/json-schema-faker/json-schema-faker) ⭐ 3,448 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-01 - Fake your schemas.
* [prmd](https://github.com/interagent/prmd) ⭐ 2,089 | 🐛 75 | 🌐 Ruby | 📅 2025-02-06 - Tools and doc generation for HTTP APIs.
* [JSON Schema $Ref Parser](https://github.com/APIDevTools/json-schema-ref-parser) ⭐ 1,112 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-14 - Parse, resolve, and dereference JSON Schema $ref pointers
* [generate-schema](https://github.com/Nijikokun/generate-schema) ⭐ 1,073 | 🐛 33 | 🌐 JavaScript | 📅 2024-01-30 - Effortlessly convert your JSON Object to JSON Schema, Mongoose Schema, or a Generic template for quick documentation / upstart.
* [Docson](https://github.com/lbovet/docson) ⭐ 497 | 🐛 44 | 🌐 JavaScript | 📅 2023-11-05 - Documentation for your types.
* [js-schema](https://github.com/molnarg/js-schema) ⭐ 386 | 🐛 21 | 🌐 JavaScript | 📅 2016-11-23 - A new way of describing object schemas in JavaScript. It has a clean and simple syntax, and it is capable of serializing to/from the popular JSON Schema format.
* [JSON Schema CLI](https://github.com/intelligence-ai/jsonschema) ⭐ 298 | 🐛 27 | 🌐 C++ | 📅 2026-08-19 - Command-line interface for formatting, linting, testing, bundling, and validating schema files for local development and CI/CD pipelines.
* [Orderly JSON](https://github.com/lloyd/orderly) ⭐ 226 | 🐛 9 | 🌐 C | 📅 2010-03-10 - A textual format for describing JSON compiled into JSONSchema.
* [Matic](https://github.com/mattyod/matic) ⭐ 180 | 🐛 3 | 🌐 JavaScript | 📅 2016-12-14 - Build tool for generating HTML documentation.
* [DLL.js](https://github.com/moll/js-ddl) ⭐ 68 | 🐛 0 | 🌐 JavaScript | 📅 2018-01-22 - Gets you a JSON Schema from PostgreSQL or SQLite3.

## JSON Schema Resources

* [Learn JSON Schema](https://www.learnjsonschema.com) - Open-source reference documentation for the schema specification.
* [Understanding JSON Schema](https://spacetelescope.github.io/understanding-json-schema/) - A website aiming to provide more accessible documentation for JSON schema.
* [Using JSON Schema](http://usingjsonschema.com/) - a Book and GitHub project, showing how JSON Schema can be used for a variety of tasks and in different programming contexts.
* [Awesome JSON Schema](https://github.com/sourcemeta/awesome-jsonschema) ⭐ 168 | 🐛 12 | 🌐 Handlebars | 📅 2026-05-12 - A curated list of awesome JSON Schema resources, tutorials, tools, and more.

## JSON Schema Validators

**Javascript and Node.js**

* [ajv](https://github.com/ajv-validator/ajv) ⭐ 14,808 | 🐛 376 | 🌐 TypeScript | 📅 2026-05-12 - The fastest schema validator. Supports draft-04/06/07/2019-09/2020-12.
* [tv4](https://github.com/geraintluff/tv4) ⭐ 1,166 | 🐛 116 | 🌐 JavaScript | 📅 2024-06-12 - Tiny Validator.
* [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) ⭐ 963 | 🐛 55 | 🌐 JavaScript | 📅 2022-08-16 - A validator that uses code generation to be extremely fast.
* [json-schema-benchmark](https://github.com/ebdrup/json-schema-benchmark) ⭐ 387 | 🐛 16 | 🌐 JavaScript | 📅 2024-07-04 - Performance benchmark for Node.js validators.
* [z-schema](https://github.com/zaggino/z-schema) ⭐ 350 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-20 - validator written in JavaScript for NodeJS and Browsers.
* [jjv](https://github.com/acornejo/jjv) ⭐ 200 | 🐛 18 | 🌐 JavaScript | 📅 2019-11-06 - Javascript Library for Schema Validation.
* [jsck](https://github.com/pandastrike/jsck) ⭐ 159 | 🐛 16 | 🌐 CoffeeScript | 📅 2017-07-21 - JSON Schema Compiled checK.
* [jsen](https://github.com/bugventure/jsen) ⭐ 155 | 🐛 7 | 🌐 JavaScript | 📅 2017-07-16 - A validator built for speed.
* [themis](https://github.com/playlyfe/themis) ⭐ 60 | 🐛 11 | 🌐 HTML | 📅 2015-10-27 - A blazing fast validator.
* [request-validator](https://github.com/bugventure/request-validator) ⭐ 0 | 🐛 1 | 🌐 JavaScript | 📅 2015-05-22 - Flexible request validator middleware for express and connect.

**Java and Kotlin**

* [Medeia Validator](https://github.com/worldturner/medeia-validator) ⭐ 60 | 🐛 23 | 🌐 Kotlin | 📅 2022-06-20 - Compliant (draft-04/06/07) and fast streaming validator written in Kotlin

**PHP**

* [JSON Schema for PHP](https://github.com/justinrainbow/json-schema) ⭐ 3,628 | 🐛 24 | 🌐 PHP | 📅 2026-08-14 - PHP implementation of JSON schema.
* [JSON Guard](https://json-guard.thephpleague.com) - A validator for JSON Schema Draft 4.

**Python**

* [jsonschema](https://github.com/python-jsonschema/jsonschema) ⭐ 4,973 | 🐛 68 | 🌐 Python | 📅 2026-08-20 - Python implementation of jsonschema.
* [JSON Schema Toolkit](https://github.com/petrounias/json-schema-toolkit) ⭐ 30 | 🐛 4 | 🌐 Python | 📅 2021-03-29 - Programmatic building of JSON schemas (recursive field mappings) with validation, a Django JSON Field, and native PostgreSQL JSON type constraints.

**Ruby**

* [Ruby JSON Schema Validator](https://github.com/voxpupuli/json-schema) ⭐ 1,643 | 🐛 105 | 🌐 Ruby | 📅 2026-07-05 - validating against a JSON schema conforming to JSON Schema Draft 4.

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-21._
