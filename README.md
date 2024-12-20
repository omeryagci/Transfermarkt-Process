# TRANSFERMARKT PROCESS

## İçindekiler - Contents

1. - TR -
   - - Genel Açıklama -
   - - Adım Adım Süreç -
   - - Robot Yolu -
   - - "Teams" Excel Örneği -
   - - Çıktı Excel Örneği -
2. - ENG -
   - - General Description -
   - - Step-by-Step Process -
   - - Robot Path -
   - - "Teams" Excel Example -
   - - Output Excel Example -

## - TR -

### - Genel Açıklama -

Merhabalar,

Transfermarkt süreci, için ilk olarak "Teams" adlı bir excel dosyası oluşturdum. Bu excel dosyası içerisinde, site üzerinde işlem yapmak istediğim takımları ekledim.
Robot ilk önce "Teams" exceline gidip bu takımlardan ilk sırada olanı alıp sitede arama yapıyor. Sonrasında takım profiline giriş yapıyor.
Takım profiline giriş yaptıktan sonra numara, oyuncu ismi, mevki, doğum tarihi ve piyasa değeri sütunlarında bulunan değerleri, takım kadrosundaki tüm oyuncular için seçiyor bir DataTable'a yazdırıyor.
Sonrasında bu DataTable'ı bir excele kaydediyor. Bu işlemleri "Teams" excelinde bulunan takım sayısı kadar tekrarlıyor ve süreci sonlandırıyor.

Teşekkürler.

### - Adım Adım Süreç -

1. "Teams" exceli okunur ve DataTable olarak kaydedilir.
2. Transfermarkt sitesi açılır.
3. DataTable için For Each Row oluşturulur.
4. Arama kısmına "Teams" excelinden alınan takım yazılır.
5. Arama butonuna tıklanır.
6. Aranan takıma tıklanır ve takım profiline girilir.
7. Kadro kısmı DataTable olarak çıkartılır.
8. İşlem yapılan takımın ismine göre dinamik excel yolu belirlenir.
9. Belirlenen excel üzerine kadro için oluşturulan DataTable yazılır.
10. Bu işlemler "Teams" excelinde bulunan tüm takımlar için For Each Row aktivitesi ile tekrarlanır.

### - Robot Yolu -

![image](https://github.com/user-attachments/assets/a606c56b-ca0d-4560-a16f-928764c1edba)

### - "Teams" Excel Örneği -

![image](https://github.com/user-attachments/assets/a96ff41b-efa9-4765-8da3-9ebd4ca384a5)

### - Çıktı Excel Örneği -

![image](https://github.com/user-attachments/assets/ceb7c3e2-d2c9-4202-872a-c56669522e44)

## - ENG -

### - General Description -

Hello,

For the Transfermarkt process, I first created an Excel file named "Teams." In this Excel file, I listed the teams I want to process on the site.
The robot first goes to the "Teams" Excel, takes the first team from the list, and performs a search on the site. Then it navigates to the team's profile.
After accessing the team profile, it selects the values in the columns for number, player name, position, date of birth, and market value for all players in the squad and writes them to a DataTable.
Next, it saves this DataTable to an Excel file. This process is repeated for as many teams as are listed in the "Teams" Excel, and the process is then completed.

Thanks.

### - Step-by-Step Process -

1. The "Teams" Excel file is read and saved as a DataTable.
2. The Transfermarkt website is opened.
3. A "For Each Row" loop is created for the DataTable.
4. The team name from the "Teams" Excel file is entered into the search field.
5. The search button is clicked.
6. The searched team is clicked, and the team profile page is opened.
7. The squad section is extracted as a DataTable.
8. A dynamic Excel path is determined based on the name of the team being processed.
9. The DataTable for the squad is written to the determined Excel file.
10. These steps are repeated for all teams in the "Teams" Excel file using the "For Each Row" activity.

### - Robot Path -

![image](https://github.com/user-attachments/assets/e71a8e7c-cd2a-4c35-831a-34a430bfca1b)

### - "Teams" Excel Example -

![image](https://github.com/user-attachments/assets/a96ff41b-efa9-4765-8da3-9ebd4ca384a5)

### - Output Excel Example -

![image](https://github.com/user-attachments/assets/ceb7c3e2-d2c9-4202-872a-c56669522e44)
