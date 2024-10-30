**Nabila Winanda Meirani**
**H1D022108**
**Praktikum Pemograman Mobile Shift D**

![App Demo](2024-10-30%2017-46-47.gif)


***Pertama-tama saya merubah tulisan pada file app.component.html untuk mengganti tulisan pada side bar***
```
<ion-list-header>Mei</ion-list-header>
          <ion-note>nabila.meirani&#64;mhs.unsoed.ac.id</ion-note>
```

***Langkah selanjutnya adalah membuat component-component pada file folder.page.html component dapat ditemukan di ionic docs*** 

1. Card
```
<div class="container">
    <ion-card>
      <ion-card-header>
        <ion-card-title>Nabila Winanda Meirani</ion-card-title>
        <ion-card-subtitle>H1D022108</ion-card-subtitle>
      </ion-card-header>
      <ion-card-content>
        Ini adalah sebuah halaman untuk latihan menggunakan components pada Ionic.
      </ion-card-content>
    </ion-card>
  </div>
```
   
2. Segment
```
<ion-segment>
    <ion-segment-button value="home">
      <ion-label>Universitas</ion-label>
    </ion-segment-button>
    <ion-segment-button value="about">
      <ion-label>Jenderal</ion-label>
    </ion-segment-button>
    <ion-segment-button value="settings">
      <ion-label>Soedirman</ion-label>
    </ion-segment-button>
  </ion-segment>
```

3. List yang mengandung checbox dan toggle
```
 <ion-list>
    <ion-list-header>
      <ion-label>Quick Actions</ion-label>
    </ion-list-header>
    
    <!-- Checkbox -->
    <ion-item>
      <ion-label>Sudah Berusia 18?</ion-label>
      <ion-checkbox slot="end"></ion-checkbox>
    </ion-item>
    
    <!-- Toggle -->
    <ion-item>
      <ion-label>Nyalakan Notifikasi</ion-label>
      <ion-toggle slot="end"></ion-toggle>
    </ion-item>
  </ion-list>
```

4. Kalender
```
<ion-item>
    <ion-label>Pilih Tanggal Lahir</ion-label>
    <ion-datetime display-format="DD/MM/YYYY"></ion-datetime>
  </ion-item>
```

5. Form dengan 3 field dan satu button
```
<ion-card>
    <ion-card-header>
      <ion-card-title>Formulir Biodata</ion-card-title>
    </ion-card-header>
    <ion-card-content>
      <ion-item>
        <ion-label position="stacked">Nama</ion-label>
        <ion-input placeholder="Nama Kamu"></ion-input>
      </ion-item>
      <ion-item>
        <ion-label position="stacked">Zodiak</ion-label>
        <ion-input type="email" placeholder="Zodiak Kamu"></ion-input>
      </ion-item>
      <ion-item>
        <ion-label position="stacked">Kata kata hari ini</ion-label>
        <ion-textarea placeholder="Kata kata"></ion-textarea>
      </ion-item>
      <ion-button expand="block" color="primary">Lets Go!</ion-button>
    </ion-card-content>
  </ion-card>
```

***Terakhir, tambahkan style CSS jika diperlukan, disini saya menggunakan style Css untuk component card. Teks CSS ditulis di file folder.page.css***
```
.container {
  text-align: center;
  margin-top: 20px;
}
```
