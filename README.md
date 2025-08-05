# bookmarks
# Архитектура и Дизайн
[Издержки микросервисов, которые ваш стартап может не потянуть](https://habr.com/ru/companies/ruvds/articles/909548/) <br>
[Базы данных. Как выбрать идеальное решение? Полный гид по SQL, NoSQL и не только](https://habr.com/ru/articles/922748/) <br>
[Распределённая трассировка с Jaeger и Clickhouse](https://habr.com/ru/companies/oleg-bunin/articles/814877/) <br>
[System Design для начинающих: всё что вам нужно. Часть 1](https://habr.com/ru/articles/873388/) <br>
[Топ 10 заповедей системного дизайна](https://habr.com/ru/articles/915376/) <br>
# Паттерны микросервисной архитектуры
[Circuit breaker, timeout, bulkhead, retry, fallback, rate limiter](https://habr.com/ru/companies/otus/articles/778574/) <br>
[Взаимодействие микросервисов: проблемы, решения, практические рекомендации](https://habr.com/ru/articles/933110/) <br>
# Проблемы из опыта
[DNS-хаос, зомби-поды и майнеры в кластере: самые невероятные случаи при работе с Kubernetes](https://habr.com/ru/companies/flant/articles/931902/) <br>
# Languages
## Golang
[Диагностика с помощью pprof в Golang](https://habr.com/ru/articles/918738/) <br>
[Application layer на примере Go](https://habr.com/ru/companies/otus/articles/913532/) <br>
[FastCGo: как мы ускорили вызов C-кода в Go в 16,5 раза](https://habr.com/ru/companies/flant/articles/923912/) <br>
[What is the consequence of using CGO_ENABLED=0?](https://www.reddit.com/r/golang/comments/pi97sp/what_is_the_consequence_of_using_cgo_enabled0/) <br>
[Потоки, горутины, синхронизация и мьютексы в Go](https://habr.com/ru/articles/933464/) <br>
# Quality Assurance
[Моки в тестировании микросервисов с кучей интеграций — кейс финтех-приложения](https://habr.com/ru/companies/agima/articles/931814/) <br>
# DBA
## Redis
[Оптимизация Redis для высоких нагрузок: полное руководство](https://habr.com/ru/companies/selectel/articles/931760/) <br>
## PostgreSQL
[Как обновить PostgreSQL и не потерять данные: метод минимизации простоя](https://habr.com/ru/companies/flant/articles/866250/) <br>
## Clickhouse
[Distributed table vs External Load Balancer + MergeTree to ReplicatedMergeTree transition](https://github.com/ClickHouse/ClickHouse/issues/2161) <br>
## Kafka
[Kafka: ребалансировка изнутри](https://habr.com/ru/companies/ozontech/articles/910568/) <br>
## Cassandra
[Развёртывание боевого кластера Cassandra. Часть 1](https://habr.com/ru/articles/924634/) <br>
# Infra
## Hardware
[Введение в SSD. Часть 2. Интерфейсная](https://habr.com/ru/companies/selectel/articles/478684/) <br>
[FC vs Ethernet (iSCSI), FC vs RoCE, FC NVMe vs FC SCSI](https://habr.com/ru/companies/jetinfosystems/articles/592703/) <br>
[Difference between RAID and HBA](https://serverfault.com/questions/616831/what-is-the-difference-between-a-hba-card-and-a-raid-card) <br>
## Networking
[L4, L7 load balancing difference](https://www.vmware.com/topics/layer-4-load-balancing) <br>
## Kubernetes
[Kubean - основанный на kubespray, ansible распилен на CRD, kubespray джобы, kubean-operator](https://kubean-io.github.io/kubean/en/) <br>
### Service Mesh
[Istio: паттерны управления трафиком, авторизация, canary, observability, проброс заголовков](https://habr.com/ru/companies/flant/articles/438426/) <br>
[Istio: mirroring, A/B, canary, timeout, retry, circuit breaker, bulkhead](https://habr.com/ru/companies/flant/articles/440378/) <br>
[Как мы внедряли Service Mesh и не утонули в сложностях: реальный кейс Orion soft](https://habr.com/ru/companies/orion_soft/articles/932118/) <br>
## Kubevirt
[KubeVirt: глубокое погружение для администраторов VMware vSphere](https://habr.com/ru/companies/flant/articles/915942/) <br>
## Containers
[Как контейнеры работают в Kubernetes](https://habr.com/ru/companies/flant/articles/913548/) <br>
[Как работают файловые системы Linux контейнеров](https://habr.com/ru/companies/flant/articles/862252/) <br>
[Что находится внутри образов distroless-контейнеров](https://habr.com/ru/companies/flant/articles/822427/) <br>
[Неиспользуемые остатки образов в Docker: как удалить зомби-слои и защитить секреты](https://habr.com/ru/companies/flant/articles/877608/) <br>
### LXC
[Туториал по контейнеризации при помощи LXC](https://eax.me/lxc/) <br>
# Storage
[Как мигрировать данные между разными StorageClass в Kubernetes и зачем это делать](https://habr.com/ru/companies/flant/articles/868280/) <br>
[Правильные, но (не)простые бэкапы. Как настроить резервное копирование в Kubernetes?](https://habr.com/ru/companies/selectel/articles/777414/) <br>
[Спокойный сон и крепкие нервы. Резервное копирование для Kubernetes. Часть 1](https://habr.com/ru/companies/otus/articles/667644/) <br>
[Способы бэкапирования Persistent Volumes в Kubernetes кластере с помощью Velero](https://habr.com/ru/articles/671706/) <br>
[LINSTOR — это как Kubernetes, но для блочных устройств (обзор и видео доклада)](https://habr.com/ru/companies/flant/articles/680286/) <br>
## Ceph
[Растянутый кластер Ceph: основные концепции. Часть 1](https://habr.com/ru/companies/runity/articles/921288/) <br>
## S3
[S3 в мире Kubernetes: как объектное хранилище сделать частью контейнеров (подход от команды Deckhouse)](https://habr.com/ru/companies/flant/articles/910938/) <br>
# O11y
## OpenTelemetry
[otel-desktop-viewer - локально смотреть данные otel-collector, и можно через otel-cli работать](https://github.com/CtrlSpice/otel-desktop-viewer) <br>
[OpenTelemetry - Injecting Auto-Instrumentation in K8S with otel-operator](https://opentelemetry.io/docs/platforms/kubernetes/operator/automatic/) <br>
[Put NGINX between two services и сбор OpenTelemetry трейсов](https://opentelemetry.io/blog/2022/instrument-nginx/) <br>
[Sending Telemetry to (& rehydrating from) AWS S3 with the OTel Collector](https://www.controltheory.com/resources/sending-telemetry-data-to-and-rehydrating-from-aws-s3-using-the-otel-collector/) <br>
[Внедрение OpenTelemetry в NAV, Автоинструментация, трудности](https://habr.com/ru/companies/flant/articles/845332/) <br>
[Convert OpenTelemetry Traces to Metrics with SpanMetrics](https://last9.io/blog/convert-opentelemetry-traces-to-metrics-using-spanconnector/) <br>
[Мониторинг бизнес процессов с помощью OpenTelemetry](https://habr.com/ru/companies/oleg-bunin/articles/865690/) <br>
[Трассировка OpenTelemetry в 200 строк кода](https://habr.com/ru/companies/beget/articles/844956/) <br>
[otel-collector gateway design](https://opentelemetry.io/docs/collector/deployment/gateway/) <br>
[Опыт внедрения otel-collector - otel-col в виде agent и agent app](https://habr.com/ru/articles/919214/) <br>
[otel-collector benchmarks](https://opentelemetry.io/docs/collector/benchmarks/) <br>
[Измерение аудитории блога с помощью OpenTelemetry](https://habr.com/ru/companies/piter/articles/902732/) <br>
[Как OpenTelemetry фиксирует ошибки](https://habr.com/ru/companies/flant/articles/892784/) <br>
[A guide to using OpenTelemetry operator for Kubernetes](https://codilime.com/blog/using-opentelemetry-operator-kubernetes/) <br>
## eBPF
[eBPF developer tutorial](https://github.com/eunomia-bpf/bpf-developer-tutorial/tree/main) <br>
[Whole-system, Cross-language OpenTelemetry eBPF profiler](https://github.com/open-telemetry/opentelemetry-ebpf-profiler) <br>
[bpfman - bpfman-agent как daemonset, bpfman-operator, ebpf программы как CRDs](https://bpfman.io/v0.5.4/quick-start/) <br>
[Network Observability eBPF Agent -  allows collecting and aggregating all the ingress and egress flows on a Linux host](https://github.com/netobserv/netobserv-ebpf-agent) <br>
[sockdump - дампим трафик с сокет файла, можно в pcap формате чтоб в wireshark открыть](https://github.com/mechpen/sockdump) <br>
[Distributed bpftrace tracing with pixie](https://blog.px.dev/distributed-bpftrace/) <br>
[Обнаружение шумных соседей с eBPF](https://habr.com/ru/companies/wunderfund/articles/859978/) <br>
[Покоряем сетевой стек Linux: декапсулируем пакеты с помощью eBPF на скорости 6Mpps+](https://habr.com/ru/companies/selectel/articles/901186/) <br>
[Катран - балансер 4го уровня на XDP, линейное масштабирование NIC RX, VIP расширяется как IP, Protocol, port ](https://github.com/facebookincubator/katran/tree/main) <br>
[Аудит по-взрослому. Применяем Tetragon на практике (и убеждаемся в силе eBPF)](https://xakep.ru/2025/04/09/ebpf-tetragon/) <br>
## Tracing
[Using FlameGraph with perf by Brendan Gregg](https://github.com/brendangregg/FlameGraph) <br>
## Metrics
[Using z-score for anomaly detection](https://about.gitlab.com/blog/anomaly-detection-using-prometheus/) <br>
[Statsd - Streaming aggregation daemon. Получает метрики на вход и отправляет в различные бекенды. Есть множество альтернативных решений на других ЯП в репе](https://github.com/statsd/statsd/tree/master) <br>
## Victoria Metrics
[VictoriaMetrics рассчёты и оптимизация](https://habr.com/ru/companies/t2/articles/922168/) <br>
[vmgateway - лимитировать запросы конкретного пользака из графаны](https://docs.victoriametrics.com/victoriametrics/vmgateway/) <br>
## Prometheus
[Analysis Prometheus memory usage](https://www.robustperception.io/analysing-prometheus-memory-usage/) <br>
[How much RAM does Prometheus 2.x need for cardinality and ingestion?](https://www.robustperception.io/how-much-ram-does-prometheus-2-x-need-for-cardinality-and-ingestion/) <br>
## Grafana
[Trace correlations](https://grafana.com/docs/grafana/latest/datasources/tempo/traces-in-grafana/trace-correlations/) <br>
[Faro Web SDK](https://github.com/grafana/faro-web-sdk/) <br>
# Генерация нагрузки, нагрузочное тестирование, бенчмаркинг
## FIO
[FIO Benchmark In-Depth Exploration Sharing](https://medium.com/@wrightchen/fio-benchmark-in-depth-exploration-sharing-f7b905c3dfcb) <br>
