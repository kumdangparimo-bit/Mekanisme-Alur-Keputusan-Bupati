markdown# Flowchart Mekanisme Alur Keputusan Bupati

## Diagram Alur Proses
```mermaid
flowchart TD
    A[1. Pengajuan SKPD] --> B[2. Checklist Kelengkapan Dokumen]
    B --> C[3. Verifikasi Administratif]
    C -->|Tidak Lengkap| D[4a. Dikembalikan untuk dilengkapi]
    D --> A
    C -->|Lengkap| E[4b. Review Substantif - Hari Kerja Mulai Dihitung]
    
    E --> F[5. Konsultasi & Perbaikan]
    F --> G[6. Finalisasi Naskah]
    G --> H[7. Paraf Koordinasi Bagian Hukum]
    H --> I[8. Paraf Pemrakarsa]
    
    I --> J[9. Paraf Asisten I/II/III]
    J --> K[10. Paraf Sekda]
    K --> L[11. Tanda Tangan Bupati]
    
    L --> M[12. Penomoran & Registrasi di Bagian Hukum]
    M --> N[Selesai - Estimasi 3-7 Hari Kerja]
    
    style A fill:#27ae60,stroke:#229954,color:#fff
    style B fill:#2ecc71,stroke:#27ae60,color:#fff
    style C fill:#2ecc71,stroke:#27ae60,color:#fff
    style D fill:#e74c3c,stroke:#c0392b,color:#fff
    style E fill:#ff9500,stroke:#ff6b35,color:#fff
    style F fill:#3498db,stroke:#2980b9,color:#fff
    style G fill:#3498db,stroke:#2980b9,color:#fff
    style H fill:#3498db,stroke:#2980b9,color:#fff
    style I fill:#3498db,stroke:#2980b9,color:#fff
    style J fill:#3498db,stroke:#2980b9,color:#fff
    style K fill:#3498db,stroke:#2980b9,color:#fff
    style L fill:#3498db,stroke:#2980b9,color:#fff
    style M fill:#3498db,stroke:#2980b9,color:#fff
    style N fill:#6c5ce7,stroke:#a29bfe,color:#fff
