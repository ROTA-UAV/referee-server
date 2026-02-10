Kamikaze Simülasyonu
curl -X POST "http://localhost:8001/kamikaze/tetikle" -H "Content-Type: application/json" -d '{"qr_metni": "hedef_kirmizi"}'

Kilitlenme Simülasyonu
curl -X POST "http://localhost:8001/kilitlenme/tetikle" -H "Content-Type: application/json" -d '{"otonom_mu": 1}'
