<script setup>
import ProductCard from '../components/ProductCard.vue'
 
const daftarProduk = [
  { id: 1, nama: 'mobil bmw', harga: 75000000, gambar: 
'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQVpLgezXuD64guymWxBrRT4_Wc2dxK5lh-fyefcKamyw&s=10' },
  { id: 2, nama: 'mobil bmw', harga: 35000000, gambar: 
'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSLcF9iY8QC2U6MxYwLVuSzN7Y-0_J4hNtIoNVkDzJiUQ&s=10' },
  { id: 3, nama: 'mobil bmw', harga: 12000000, gambar: 
'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSdl9oGLU_0GwDOAxwiAyMBS9nqcbDuNW_Fxo9rxK_UXw&s=10' },
  { id: 4, nama: 'mobil bmw', harga: 15000000, gambar:
    'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRXCzgOvS-1H4wkt0jqYii1Jj06KmDsD2XMvoiP76C__Q&s=10'},
  { id: 5, nama: 'mobil bmw', harga: 16000000, gambar:
  'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTwNAbUoGiU-8ihHZs0eAMDEzzMIgVwPktKlQ06gCy_EQ&s=10'}
]
</script>
 
<template>
  <main>
    <h1>Produk Kami</h1>
    <div class="grid">
      <ProductCard
        v-for="produk in daftarProduk"
        :key="produk.id"
        :nama="produk.nama"
        :harga="produk.harga"
        :gambar="produk.gambar"
      />
    </div>
  </main>
</template>
 
<style scoped>
.grid {
  display: flex;
  gap: 16px;
  flex-wrap: wrap;
  
}
</style>