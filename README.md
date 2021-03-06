# go-list
<p>A curated list of great Go resources (articles, conferences, tutorials, etc). I maintain it mostly for myself, but why not share with everyone?:)</p>
<p align="center"><img src="https://pbs.twimg.com/profile_images/717802216824840192/epO_pg3z.jpg" width="350px" alt="gopher with books"></img></p>

## Concurrency
* https://github.com/golang/go/wiki/LearnConcurrency
* https://blog.acolyer.org/2019/05/17/understanding-real-world-concurrency-bugs-in-go/
* https://medium.com/dm03514-tech-blog/golang-monitors-and-mutexes-a-light-survey-84f04f9b7c09
* [GopherCon UK 2018: Roberto Clapis - Goroutines: The Dark Side of the Runtime](https://youtu.be/4CrL3Ygh7S0)
* [Rob Pike - 'Concurrency Is Not Parallelism'](https://youtu.be/cN_DpYBzKso)
* [GopherCon 2018: Bryan C. Mills - Rethinking Classical Concurrency Patterns](https://youtu.be/5zXAHh5tJqQ)
* [Golang UK Conference 2017 | Arne Claus - Concurrency Patterns in Go](https://youtu.be/rDRa23k70CU)
* [Golang UK Conference 2015 - Evan Huus - Complex Concurrency Patterns with Go](https://youtu.be/2HOO5gIgyMg)
## Perfomance
* https://medium.com/@valyala/mmap-in-go-considered-harmful-d92a25cb161d
* https://medium.freecodecamp.org/million-websockets-and-go-cc58418460bb
* https://www.akshaydeo.com/blog/2017/12/23/How-did-I-improve-latency-by-700-percent-using-syncPool/
* https://blog.twitch.tv/go-memory-ballast-how-i-learnt-to-stop-worrying-and-love-the-heap-26c2462549a2
* https://appliedgo.net/concurrencyslower/
* https://omgnull.github.io/go-benchmark/buffer/
* http://herman.asia/efficient-string-concatenation-in-go
* https://github.com/dgryski/go-perfbook
* https://github.com/golang/go/wiki/Performance
* https://adrummond.net/posts/gogenerics
* https://github.com/jeromefroe/golang_benchmarks
* https://medium.com/@blanchon.vincent/go-should-i-use-a-pointer-instead-of-a-copy-of-my-struct-44b43b104963
* https://dave.cheney.net/high-performance-go-workshop/gophercon-2019.html
* https://stephen.sh/posts/quick-go-performance-improvements
* https://segment.com/blog/allocation-efficiency-in-high-performance-go-services/
* https://github.com/go101/go101/wiki/The-perceivable-optimizations-made-by-the-standard-Go-compiler-%28gc%29
* [dotGo 2019 - Bryan Boreham - Go Tune Your Memory](https://www.youtube.com/watch?v=uyifh6F_7WM)
* [Работа с сетью в Go. Алексей Акулович, Вконтакте.](https://youtu.be/p1ILhiq5Clw)
* [Golang UK Conference 2017 | Guido Patanella - Go routines optimization](https://youtu.be/yo-CkroaQhs)
* [GopherCon 2018: Eben Freeman - Allocator Wrestling](https://youtu.be/M0HER1G5BRw)
* [GopherCon 2017: Peter Bourgon - Evolutionary Optimization with Go](https://youtu.be/ha8gdZ27wMo)
* [Golang UK Conference 2016 - Travis Bischel - When Idioms Become Bottlenecks](https://youtu.be/q7s30kFHBdw)
* [dotGo 2019 - Daniel Martí - Optimizing Go code without a blindfold](https://youtu.be/jiXnzkAzy30)
* [dotGo 2019 - Roberto Clapis - The monsters inside the sync.Locker](https://youtu.be/Y0ZfZnN0lB8)
## Go-nuts
* https://morsmachine.dk/go-scheduler
* https://morsmachine.dk/netpoller
* http://dmitryvorobev.blogspot.com/2016/08/golang-channels-implementation.html
* https://medium.com/i0exception/runtime-overhead-of-using-defer-in-go-7140d5c40e32
* https://medium.com/@ggiovani/tcp-socket-implementation-on-golang-c38b67c5d8b
* https://github.com/golang/go/wiki/CompilerOptimizations
* https://golang.org/ref/mem
* https://github.com/teh-cmc/go-internals
* https://groups.google.com/forum/#!msg/Golang-Nuts/ENgbUzYvCuU/90yGx7GUAgAJ
* https://docs.google.com/document/d/1TTj4T2JO42uD5ID9e89oa0sLKhJYD0Y_kqxDv3I3XMw/edit
* https://itnext.io/manipulating-private-fields-in-go-4da4ca525717
* https://medium.com/@blanchon.vincent/go-buffered-and-unbuffered-channels-29a107c00268
* https://medium.com/@blanchon.vincent/go-how-does-the-goroutine-stack-size-evolve-447fc02085e5
* https://medium.com/@blanchon.vincent/go-how-does-defer-statement-work-1a9492689b6e
* https://medium.com/a-journey-with-go/go-how-does-the-garbage-collector-watch-your-application-dbef99be2c35
* https://blog.ankuranand.com/2018/09/29/diving-deep-into-the-golang-channels/
* https://povilasv.me/go-memory-management/
* https://blog.ankuranand.com/2019/02/20/a-visual-guide-to-golang-memory-allocator-from-ground-up/
* https://blog.minio.io/golang-internals-part-1-autogenerated-functions-and-how-to-get-rid-of-them-6ca4749cc236
* https://www.ardanlabs.com/blog/2018/08/scheduling-in-go-part1.html
* https://www.ardanlabs.com/blog/2018/12/garbage-collection-in-go-part1-semantics.html
* https://www.ardanlabs.com/blog/2017/05/language-mechanics-on-stacks-and-pointers.html
* https://medium.com/i0exception/map-iteration-in-go-275abb76f721
* [Как устроен garbage collector в Go 1.9 - Андрей Дроздов, Avito](https://youtu.be/CX4GSErFenI)
## Go tools
* https://www.alexedwards.net/blog/an-overview-of-go-tooling
* https://medium.com/@blanchon.vincent/go-vet-command-is-more-powerful-than-you-think-563e9fdec2f5
* https://blog.golang.org/using-go-modules
* https://github.com/go-modules-by-example/index/tree/master/018_go_list_mod_graph_why
## Testing
* https://dave.cheney.net/2019/05/07/prefer-table-driven-tests
* http://cs-guy.com/blog/2015/01/test-main/
* https://blog.alexellis.io/golang-writing-unit-tests/
* https://medium.com/@povilasve/go-advanced-tips-tricks-a872503ac859
* https://deliveroo.engineering/2019/05/17/testing-go-services-using-interfaces.html
* https://github.com/golang/go/wiki/TestComments
* https://medium.com/a-journey-with-go/go-fuzz-testing-in-go-deb36abc971f
* [LondonGophers 20/03/2019: Dave Cheney - Absolute Unit (Test)](https://youtu.be/UKe5sX1dZ0k)
## Benchmarking/Profiling
* https://habr.com/ru/company/badoo/blog/301990/
* https://scene-si.org/2017/06/06/benchmarking-go-programs/
* https://medium.com/@fzambia/bisecting-go-performance-degradation-4d4a7ee83a63
* https://medium.com/@hackintoshrao/daily-code-optimization-using-benchmarks-and-profiling-in-golang-gophercon-india-2016-talk-874c8b4dc3c5
* https://artem.krylysov.com/blog/2017/03/13/profiling-and-optimizing-go-web-applications/
* http://morsmachine.dk/http2-causalprof
## Writing Go code
* https://dave.cheney.net/practical-go/presentations/qcon-china.html
* https://medium.com/statuscode/how-i-write-go-http-services-after-seven-years-37c208122831
* https://github.com/golang/go/wiki/CodeReviewComments
* https://golang.org/doc/code.html
* https://golang.org/doc/effective_go.html
* https://peter.bourgon.org/blog/2019/04/24/go-naming-tips.html
* https://blog.golang.org/using-go-modules
* https://medium.com/@mustafaturan/decoupled-package-communication-in-go-6c60085ed25b
* https://dave.cheney.net/2019/07/09/clear-is-better-than-clever
* https://github.com/golang-standards/project-layout
* https://github.com/Pungyeon/clean-go-article
* https://medium.com/@benbjohnson/structuring-applications-in-go-3b04be4ff091
* https://dev.to/eminetto/object-calisthenics-in-golang-1h75
* https://medium.com/@cep21/how-to-correctly-use-context-context-in-go-1-7-8f2c0fafdf39
* https://github.com/uber-go/guide/blob/master/style.md
* https://blog.usejournal.com/function-currying-in-go-a88672d6ebcf
* https://blog.golang.org/go1.13-errors
* [dotGo 2016 - Dave Cheney - Do not fear first class functions](https://youtu.be/5buaPyJ0XeQ)
* [dotGo 2019 - Dave Cheney - Constant Time](https://youtu.be/pN_lm6QqHcw)
* [GopherCon 2018: Kat Zien - How Do You Structure Your Go Apps](https://youtu.be/oL6JBUk6tj0)
* [7 common mistakes in Go and when to avoid them by Steve Francia (Docker)](https://youtu.be/29LLRKIL_TI)
* [Golang UK Conference 2016 - Mat Ryer - Idiomatic Go Tricks](https://youtu.be/yeetIgNeIkc)
## Language details
* https://www.callicoder.com/golang-typed-untyped-constants/
* https://golang.org/ref/spec
* https://golang.org/pkg/
* https://github.com/golang/go/wiki/SliceTricks
* https://medium.com/@Martynas/formatting-date-and-time-in-golang-5816112bf098
* https://medium.com/@blanchon.vincent/go-what-is-the-unsafe-package-d2443da36350
* https://medium.com/@blanchon.vincent/go-context-and-cancellation-by-propagation-7a808bbc889c
* https://medium.com/@blanchon.vincent/go-finalizers-786df8e17687
* https://medium.com/yakka/better-go-error-handling-with-xerrors-1987650e0c79
* https://medium.com/vendasta/golang-pointer-receivers-and-error-pointer-returns-421b5b21a020
* https://medium.com/golangspec/methods-in-go-part-i-a4e575dff860
* https://medium.com/golangspec/interfaces-in-go-part-i-4ae53a97479c
* https://medium.com/rungo/everything-you-need-to-know-about-packages-in-go-b8bac62b74cc
* https://golangbot.com/custom-errors/
* [GopherCon 2016: Francesc Campoy - Understanding nil](https://youtu.be/ynoY2xz-F8s)
* [Golang UK Conference 2016 - Paul Crawford - A Beginners Guide to Context](https://youtu.be/r4Mlm6qEWRs)
* [dotGo 2019 - James Bowes - Shattered Mirror: An Introduction to Reflect and Unsafe](https://www.youtube.com/watch?v=ZJFMvWHtSAA)
## Courses
* [Программирование на Go Технострим Mail.Ru Group](https://www.youtube.com/watch?v=9Pk7xAT_aCU&list=PLrCZzMib1e9q-X5V9pTM6J0AemRWseM7I)
* [Разработка веб-сервисов на Go - основы языка](https://www.coursera.org/learn/golang-webservices-1)
* [Разработка веб-сервисов на Golang, часть 2](https://www.coursera.org/learn/golang-webservices-2)
## Books
* https://www.packtpub.com/networking-and-servers/mastering-go
* https://go101.org/article/101.html
* https://www.amazon.com/Concurrency-Go-Tools-Techniques-Developers/dp/1491941197
## Go philosophy 
* https://www.cs.cmu.edu/~crary/819-f09/Hoare78.pdf
* [dotGo 2015 - Rob Pike - Simplicity is Complicated](https://youtu.be/rFejpH_tAHM)
* [OSCON 2010: Rob Pike, "Public Static Void"](https://youtu.be/5kj5ApnhPAE)
* [Go Proverbs - Rob Pike - Gopherfest - November 18, 2015](https://youtu.be/PAAkCSZUG1c)
* [GopherCon 2016: Rob Pike - The Design of the Go Assembler](https://youtu.be/KINIAgRpkDA)
## In practice
* https://engineering.mixpanel.com/2019/07/24/safely-rewriting-mixpanels-highest-throughput-service-in-golang/
* https://yalantis.com/blog/go-application-performance-monitoring/
* https://medium.com/a-journey-with-go/go-elasticsearch-clients-study-case-dbaee1e02c7
* https://medium.com/@valyala/improving-histogram-usability-for-prometheus-and-grafana-bc7e5df0e350
* https://medium.com/tourradar/working-efficiently-with-json-in-go-cb80dcca0466
* https://medium.com/@mssr/the-circuit-breaker-pattern-85e28c8e01b7
* https://www.bugsnag.com/blog/microservice-developer-tools-for-gophers
## Awesome authors
* [Dave Cheney](https://dave.cheney.net/)
* [Dmitry Vyukov](http://www.1024cores.net/)
* [Vincent Blanchon](https://medium.com/@blanchon.vincent)
* [Bill Kennedy](https://twitter.com/goinggodotnet)
## Awesome resources
* https://rakyll.org/archive/
* https://golang.org/doc/
* https://github.com/golang/go/wiki
* https://www.reddit.com/r/golang/
* https://gobyexample.com/
* https://github.com/tmrts/go-patterns
* https://github.com/dariubs/GoBooks
* http://www.go-gazette.com/
* https://github.com/quii/learn-go-with-tests
* https://www.calhoun.io/guide-to-go/
* https://github.com/hoanhan101/ultimate-go
## Conference YouTube channels/playists
* [Gopher Academy](https://www.youtube.com/channel/UCx9QVEApa5BKLw9r8cnOFEA)
* [GopherCon Russia](https://www.youtube.com/channel/UCq-OB01F8YnS-FJpeJRCvMQ)
* [GopherCon UK](https://www.youtube.com/channel/UC9ZNrGdT2aAdrNbX78lbNlQ)
* [London Gophers](https://www.youtube.com/channel/UCZPhOgp4kDXkg2W8jL4U7GA)
* [Sigapore Gophers](https://www.youtube.com/channel/UCazkIMpjghmT8fugD1WF_DQ)
* [Go Conferences | Golang | Gophercon playlist](https://www.youtube.com/playlist?list=PLuKvd2GQmvCATHrdPfWwESh6o8AI4GTpj)
## Other
* https://spacetime.dev/to-slice-or-not-to-slice
* https://www.joeshaw.org/dont-defer-close-on-writable-files/
* http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/index.html
* https://itnext.io/the-top-10-most-common-mistakes-ive-seen-in-go-projects-4b79d4f6cd65
* https://eli.thegreenplace.net/2019/passing-callbacks-and-pointers-to-cgo/
