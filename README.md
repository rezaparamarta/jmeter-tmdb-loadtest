# JMeter Load Test - TMDB API

Load testing endpoint `/3/person/changes?page=1` menggunakan Apache JMeter.

## Spec
- Threads: 2
- Ramp-up: 10 detik
- Duration: 60 detik
- Auth: api_key query parameter (decoded from JWT)

## Hasil
- 447 samples
- 100% success (200 OK)
- Avg response time: 256.26 ms
- Throughput: 7.46 req/sec

Buka folder `tmdb-report-final/index.html` untuk dashboard lengkap.
