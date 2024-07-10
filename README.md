# Vector Database

Bu proje, gömme (embedding) vektörlerini depolamak ve sorgulamak için basit bir veritabanı sunar.

# Kurulum

Proje kullanılmadan önce aşağıdaki adımları izleyin:

1. Python ve PostgreSQL kurulu olmalıdır.
2. Projenin gereksinimlerini yüklemek için aşağıdaki komutu çalıştırın:
pip install -r requirements.txt


3. PostgreSQL veritabanı oluşturun ve bağlantı bilgilerini `config.py` dosyasına ekleyin.

# Kullanım

Proje, gömme vektörlerini depolamak ve sorgulamak için kullanılabilir.

1. `add_vectors.py` dosyasını kullanarak vektörleri veritabanına ekleyin.
2. `query_vectors.py` dosyasını kullanarak belirli bir metinle ilişkilendirilmiş bir vektörü sorgulayın.

Örnek kullanım:
python add_vectors.py --text "Bu bir örnek metindir." --vector [0.1, 0.2, 0.3]
python query_vectors.py --text "Bu bir örnek metindir."

