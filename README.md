--[TR]--

Merhabalar,

Transfermarkt süreci, için ilk olarak "Teams" adlı bir excel dosyası oluşturdum. Bu excel dosyası içerisinde, site üzerinde işlem yapmak istediğim takımları ekledim.
Robot ilk önce "Teams" exceline gidip bu takımlardan ilk sırada olanı alıp sitede arama yapıyor. Sonrasında takım profiline giriş yapıyor.
Takım profiline giriş yaptıktan sonra numara, oyuncu ismi, mevki, doğum tarihi ve piyasa değeri sütunlarında bulunan değerleri, takım kadrosundaki tüm oyuncular için seçiyor bir DataTable'a yazdırıyor.
Sonrasında bu DataTable'ı bir excele kaydediyor. Bu işlemleri "Teams" excelinde bulunan takım sayısı kadar tekrarlıyor ve süreci sonlandırıyor.

Teşekkürler.

--[ENG]--

Hello,

For the Transfermarkt process, I first created an Excel file named "Teams." In this Excel file, I listed the teams I want to process on the site.
The robot first goes to the "Teams" Excel, takes the first team from the list, and performs a search on the site. Then it navigates to the team's profile.
After accessing the team profile, it selects the values in the columns for number, player name, position, date of birth, and market value for all players in the squad and writes them to a DataTable.
Next, it saves this DataTable to an Excel file. This process is repeated for as many teams as are listed in the "Teams" Excel, and the process is then completed.

Thanks.

--"Teams" Excel Example--

![image](https://github.com/user-attachments/assets/a96ff41b-efa9-4765-8da3-9ebd4ca384a5)

--Output Excel Example--

![image](https://github.com/user-attachments/assets/ceb7c3e2-d2c9-4202-872a-c56669522e44)
