# [VIDEO ANLATIM](https://drive.google.com/file/d/1z-8LtiMe5iu08AZHPeJtveR7bJSRMCxR/view?usp=sharing)

# Proje Amacı
Bu proje, Bu projenin temel amacı, 250 düğümlük karmaşık bir ağ topolojisi üzerinde gecikme, güvenilirlik ve bant genişliği metriklerini dikkate alarak bir kaynaktan (S) bir hedefe (D) giden "en iyi" yolu bulmaktır.

## Seed Bilgisi
Rastgele sayıların tekrar üretilebilirliği için seed kullanılmıştır:

```python
import random
import numpy as np

SEED = 42
random.seed(SEED)
np.random.seed(SEED)
```
## Projenin Kurulumu ve Çalıştırılması
Bu proje Python `venv` sanal ortamı kullanılarak geliştirilmiştir. Projeyi kendi
bilgisayarınıza kurmak ve çalıştırmak için aşağıdaki adımları takip edin.

### 1. Gerekli Araçların Kurulu Olup Olmadığını Kontrol Etme
Git, Python ve pip’in sisteminizde kurulu olduğundan emin olun.
İşletim sisteminize göre kurulum adımlarına aşağıdaki bağlantılardan ulaşabilirsiniz:

[Kurulum](docs/MD/setup.md)

### 2. Repoyu klonlayın
```bash
git clone <repo-linki>
```

### 3. Proje klasörüne girin
```bash
cd <proje-klasörü>
```

### 4. Sanal ortamı oluşturun
Proje klasörü içinde aşağıdaki komutu çalıştırın:
```bash
python -m venv venv
```
Bu komut, proje için izole bir Python sanal ortamı (```venv```) oluşturur.

### 5. Sanal ortamı aktifleştirin
Windows
```powershell
venv\Scripts\activate
```
macOS/Linux
```bash
source venv/bin/activate
```

### 6. Gerekli kütüphaneleri indirin
```bash
python -m pip install -r requirements.txt
```

### 7. Uygulamayı çalıştırın
```bash
python -m streamlit run  main.py
```
