Что нужно уметь и знать чтобы быть крутым Go-разработчиком?

**Golang:**

- Методы. Value receiver vs pointer receiver. Embedding. Method value. Encapsulation. Интерфейсы. Интерфейсы как контракты. io.Writer, io.Reader и их реализации. sort.Interface. error. http.Handler. Интерфейсы как перечисления. Type assertion. Type switch. The bigger the interface, the weaker the abstraction. Обработка ошибок. panic, defer, recover. errors.{Unwrap,Is,As}. fmt.Errorf. %w.

- Горутины и каналы. clock server. echo server. Размер канала. Блокирующее и неблокирующее чтение. select statement. Channel axioms. time.After. time.NewTicker. Pipeline pattern. Cancellation. Parallel loop. sync.WaitGroup. Обработка ошибок в параллельном коде. errgroup.Group. Concurrent web crawler. Concurrent directory traversal.

- Продвинутое тестирование. Subtests. *testing.B. (*T).Logf. (*T).Skipf. (*T).FailNow. testing.Short(), testing flags. Генерация моков. testify/{require,assert}. testify/suite. Test fixture. Интеграционные тесты. Goroutine leak detector. TestingMain. Coverage. Сравнение бенчмарков.

- Concurrency with shared memory. sync.Mutex. sync.RWMutex. sync.Cond. atomic. sync.Once. Race detector. Async cache. Package context. context.WithTimeout.

- net/http. Passing request-scoped data. http middleware. chi.Router .Graceful server shutdown.

- database/sql, sqlx, работа с базами данных, redis.

- Reflection. reflect.Type and reflect.Value. struct tags. net/rpc. encoding/gob. sync.Map. reflect.DeepEqual.

- Пакет io, реализации Reader и Writer из стандартной библиотеки. Low-level programming. unsafe. Package binary. bytes.Buffer. cgo, syscall.

- Архитектура GC. Write barrier. Stack growth. GC pause. GOGC. sync.Pool. Шедулер горутин. GOMAXPROCS. Утечка тредов.

- Go tooling. pprof. CPU and Memory profiling. Кросс-компиляция. GOOS, GOARCH. CGO_ENABLED=0. Build tags. go modules. godoc. Code generation.

- go/types и x/analysis. Статический анализ го кода.


