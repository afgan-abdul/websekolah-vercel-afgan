<template>
    <div class="kolom">
        <div class="teks">
            <h1>Cerita Kami</h1>
            <p>Online shop ini merupakan situs yang di kembangkan oleh Afgan sebagai siswa SMK YADIKA SOREANG,
               dan sampai saat kalian membaca situs ini masih dalam proses pengembangan,
               kami berharap online shop ini bukan hanya proyek tugas sekolah melain bisa saya kembangkan untuk saya sendiri</p>
        </div>
        <div class="gambar">
            <img src="/gambar/bmw.jpeg" alt="Toko Bmw">
        </div>
    </div>
</template>

<style scoped>
.kolom{
    font-family: 'Segoe UI', sans-serif;
    display: flex;
    align-items: flex-start;
    margin: 50px;
    flex: 1;
    flex-direction: row;
    overflow: hidden;
}

.gambar img{
    width: 600px;
    height: auto;
    border-radius: 10px;
}

.teks{
    flex: 1;
}

.teks h1{
    background: #28068f;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    margin-bottom: 10px;
}

.teks p{
    margin-top: 0;
}
</style>