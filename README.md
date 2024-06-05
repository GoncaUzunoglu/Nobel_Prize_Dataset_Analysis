# Nobel Ödülü Veriseti Analizi

Bu proje, Nobel Ödülü verisetini analiz ederek, Nobel Ödüllerini en çok kazanan ülkeleri, ilk kadın ve erkek kazananları ve belirli dönemlerdeki kazananların kategorilerini ve ülkelerini belirlemeyi amaçlamaktadır. Python kullanılarak veri analizi ve görselleştirme yapılmıştır.

## Veriseti Bilgileri

Bu analizde kullanılan veriseti aşağıdaki sütunları içerir:

- **year**: Nobel Ödülü'nün verildiği yıl.
- **category**: Nobel Ödülü kategorisi (örneğin, Kimya, Edebiyat, Tıp, Barış).
- **prize**: Verilen özel Nobel Ödülü.
- **motivation**: Ödülün verilme nedeni.
- **prize_share**: Ödülün payı.
- **laureate_id**: Ödül sahibinin benzersiz kimliği.
- **laureate_type**: Ödül sahibinin türü (örneğin, Bireysel).
- **full_name**: Ödül sahibinin tam adı.
- **birth_date**: Ödül sahibinin doğum tarihi.
- **birth_city**: Ödül sahibinin doğum yeri (şehir).
- **birth_country**: Ödül sahibinin doğum yeri (ülke).
- **sex**: Ödül sahibinin cinsiyeti.
- **organization_name**: Ödül sahibinin bağlı olduğu kuruluşun adı.
- **organization_city**: Kuruluşun bulunduğu şehir.
- **organization_country**: Kuruluşun bulunduğu ülke.
- **death_date**: Ödül sahibinin ölüm tarihi (varsa).
- **death_city**: Ödül sahibinin ölüm yeri (şehir) (varsa).
- **death_country**: Ödül sahibinin ölüm yeri (ülke) (varsa).

## Kurulum

Bu projeyi çalıştırmak için aşağıdaki Python kütüphanelerini yüklemeniz gerekmektedir:

```bash
pip install pandas seaborn matplotlib numpy
