# JMeter Load Test - TMDB API

Load testing endpoint `/3/person/changes?page=1` menggunakan Apache JMeter.

## Spec
- Threads: 2
- Ramp-up: 10 detik
- Duration: 60 detik
- Auth: api_key query parameter (decoded from JWT)

## Hasil
- 502 samples
- 100% success (200 OK)
- Avg response time: 228 ms
- Throughput: 8.36 req/sec

Buka folder `tmdb-report-final/index.html` untuk dashboard lengkap.
