# bookmarks
# Архитектура и Дизайн
[Издержки микросервисов, которые ваш стартап может не потянуть](https://habr.com/ru/companies/ruvds/articles/909548/) <br>
[Базы данных. Как выбрать идеальное решение? Полный гид по SQL, NoSQL и не только](https://habr.com/ru/articles/922748/) <br>
[Распределённая трассировка с Jaeger и Clickhouse](https://habr.com/ru/companies/oleg-bunin/articles/814877/) <br>
[System Design для начинающих: всё что вам нужно. Часть 1](https://habr.com/ru/articles/873388/) <br>
[Топ 10 заповедей системного дизайна](https://habr.com/ru/articles/915376/) <br>
# Languages
## Golang
[Диагностика с помощью pprof в Golang](https://habr.com/ru/articles/918738/) <br>
[Application layer на примере Go](https://habr.com/ru/companies/otus/articles/913532/) <br>
[FastCGo: как мы ускорили вызов C-кода в Go в 16,5 раза](https://habr.com/ru/companies/flant/articles/923912/) <br>
# DBA
## Clickhouse
[Distributed table vs External Load Balancer + MergeTree to ReplicatedMergeTree transition](https://github.com/ClickHouse/ClickHouse/issues/2161) <br>
## Kafka
[Kafka: ребалансировка изнутри](https://habr.com/ru/companies/ozontech/articles/910568/) <br>
## Cassandra
[Развёртывание боевого кластера Cassandra. Часть 1](https://habr.com/ru/articles/924634/) <br>
# Infra
## Kubernetes
[Kubean - основанный на kubespray, ansible распилен на CRD, kubespray джобы, kubean-operator](https://kubean-io.github.io/kubean/en/) <br>
## Kubevirt
[KubeVirt: глубокое погружение для администраторов VMware vSphere](https://habr.com/ru/companies/flant/articles/915942/) <br>
## Containers
### LXC
[Туториал по контейнеризации при помощи LXC](https://eax.me/lxc/) <br>
# Storage
## Ceph
[Растянутый кластер Ceph: основные концепции. Часть 1](https://habr.com/ru/companies/runity/articles/921288/) <br>
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
