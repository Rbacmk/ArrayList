# ArrayList
///ArrayList
           /// Bir koleksiyon tipidir.
           /// İçerisinde birden veri taşıyabiliriz. Dinamik yapıdadır.
          ArrayList liste= new ArrayList();// İlk önce arraylisti tanımladık.
            
            liste.Add("Ayşe");
            liste.Add(2);
            liste.Add(true);// Listemize eleman ekledik.

            //İçerisindeki verilere erişim
            Console.WriteLine(liste[1]);// 1 'inci index teki veriyi getirir.
             
            foreach (var item in liste)
                Console.WriteLine(item);// Böylelikle liste içerisindeki tüm elemanları yazdırmış oluruz.

            // AddRange
            // Birden fazla elemanı toplu halde eklememizi sağlar.
            string[] renkler = { "kırmızı", "mavi", "yeşil" };// Dizi oluşturduk.
            List<int> sayılar = new List<int>() { 1, 2, 5, 6, 8, 96 };
            liste.AddRange(renkler);// Diziye eleman ekledik.
            liste.AddRANGE(sayılar);
            foreach (var item in liste)// Ekrana listenin elemanlarını yazdırdık.
                Console.WriteLine(item);

            // Sort
            Console.WriteLine("******sort******");
            liste.Sort();// Sort elemanı sıralamaya yardımcı olur.

            foreach (var item in liste)// Ekrana listenin elemanlarını yazdırdık.
                Console.WriteLine(item);



            // Binary Search
            Console.WriteLine("****Binary Search******");
            liste.WriteLine(liste.BinarySearch(9));
            //Reverse
            liste.Reverse();// Tersten sıralıyor.
            foreach (var item in liste)// Ekrana listenin elemanlarını yazdırdık.
                Console.WriteLine(item);
            Console.WriteLine(item);
