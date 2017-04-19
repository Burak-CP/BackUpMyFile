# BackupMyFile - Dosya Yedekleme Program�
BackupMyFile yedekleme i�lerinizi kolay ve h�zl� �ekilde tamamlaman�z� sa�layan bir yaz�l�md�r. Bu yaz�l�mla verilerinizi bilgisayar�n depolama ayg�tlar�ndan belirleyece�iniz herhangi birisine veya USB depolama ayg�t�n�za kaydedebilirsiniz.

# �zellikler:
 - Manual backup
 - Auto backup
   - Dosya de�i�ti�inde backup
   - Periyodik backup
 - Backup h�z� (0-20 aras�, 0 h�zl�)
	
# Koddan exe dosyas�n� elde etme(Build i�lemi):
  - Zip dosyas�n� a��n ve BackUpMyFile.sln'i Visual Studio 2015 ile �al��t�r�n. 
  - Solution Explorer penceresinden projenin �zerine sa� tu� t�klayarak build se�ene�ine t�klay�n.
  - ".exe" uzant�l� dosyay� ...\BackUpMyFile\BackUpMyFile\bin\(Debug veya Release) klas�r�n�n i�erisinde bulacaks�n�z.
 
# Kullan�m�:
  - Yedekleme i�lemini anl�k olarak yapmak istiyorsan�z yapman�z gereken �Source� k�sm�na �ift t�klayarak yede�ini almak istedi�iniz klas�r�n yolunu ve �Destination� k�sm�na �ift t�klayarak yede�i kopyalamak istedi�iniz klas�r�n yolunu belirtmeniz. Daha sonra �Backup� butonuna t�klaman�z yeterli olacakt�r.
  - Auto backup �zelli�ini a�mak i�in taskbardan(sa�atin oldu�u yer) program�n simgesine sa� tu� t�klay�n ve "Options" se�ene�ini se�in. A��lan pencerede "Auto Backup" kutucu�unu se�ili hale getirin.
  - Yedekleme i�lemini belirli zaman aral�klar�yla yapmak istiyorsan�z �Source� ve �Destination� k�sm�n� yukar�daki gibi yapt�ktan sonra �Backup Method� kutucu�undan "Periodically" se�ene�ini se�erek sa��nda g�r�necek kutuya saniye cinsinden zaman� girmeniz ve "Add" butonuna t�klayarak kaydetmeniz gerekiyor.
  - Yedekleme i�lemini her hangi bir dosya de�i�ti�inde yapmak istiyorsan�z �Source� ve �Destination� k�sm�n� yukar�daki gibi yapt�ktan sonra �Backup Method� kutucu�undan "When file changed" se�ene�ini se�meniz ve "Add" butonuna t�klayarak kaydetmeniz gerekiyor.
  - Daha �nce kaydetti�iniz bir backup �zerinde de�i�iklik yapmak i�in, "Archive" butonuna t�klay�n�z. A��lan pencerede de�i�iklik yapmak istedi�iniz backup'� se�in. Silmek i�in "Delete" butonuna t�klay�n. De�i�tirmek i�in ise "Select" butonuna t�klayarak de�i�iklikleri yap�n ve "Add butonuna t�klay�n."
  - Copyalama h�z�n� belirlemek i�in taskbardan(sa�atin oldu�u yer) program�n simgesine sa� tu� t�klay�n ve "Options" se�ene�ini se�in. A��lan pencerede "Speed choice" kutucu�undan h�z�n� belirleyebilirsiniz.

[burakkocaman.com](http://burakkocaman.com/dosya-yedekleme-programibackupmyfile/)

[github/Burak-CP](https://github.com/Burak-CP/BackUpMyFile/)