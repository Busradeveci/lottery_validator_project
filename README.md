Bu Python betiği, `lottery_numbers.csv` dosyasındaki hatalı biçimlendirilmiş satırları filtreler ve yalnızca geçerli olanları `correct_numbers.csv` dosyasına kaydeder. 

**Özellikler:**

- `lottery_numbers.csv` dosyasındaki her satırı kontrol eder.
- Geçerli biçimde olmayan satırları filtreler.
- Geçerli satırları `correct_numbers.csv` dosyasına yazar.

**Kullanılan Teknolojiler:**

- Python

**Kurulum ve Kullanım:**

1. Depoyu klonlayın:

   ```bash
   git clone https://github.com/Busradeveci/lottery_validator_project.git
   ```

2. Gerekli bağımlılıkları yükleyin (varsa):

   ```bash
   pip install -r requirements.txt
   ```

3. `lottery_validator.py` dosyasını çalıştırın:

   ```bash
   python lottery_validator.py
   ```

4. `correct_numbers.csv` dosyasını kontrol ederek geçerli satırları görüntüleyebilirsiniz.
