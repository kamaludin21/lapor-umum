<template>
  <div class="flex flex-col md:flex-row space-x-0 md:space-x-6 space-y-4 md:space-y-0">
    <div class="w-full md:w-2/5 space-y-2">
      <p class="text-3xl font-bold tracking-wide text-slate-800">Layanan Aspirasi dan Pengaduan Online Rakyat</p>
      <p class="text-lg font-normal text-slate-700">Sampaikan laporan Anda langsung kepada instansi pemerintah berwenang
      </p>
    </div>
    <div class="w-full md:w-3/5 bg-white border border-slate-400 p-2 md:p-4 rounded-xl">
      <p class="text-lg font-medium">Formulir Laporan</p>
      <hr>
      <div class="grid gap-4 mt-4">
        <div>
          <label for="first_name" class="block mb-1 text-sm font-medium text-gray-900 ">Judul Laporan</label>
          <input type="text" id="first_name"
            class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5"
            placeholder="John" required />
        </div>
        <div>
          <label for="message" class="block mb-2 text-sm font-medium text-gray-900">Keterangan</label>
          <textarea id="message" rows="4"
            class="block p-2.5 w-full text-sm text-gray-900 bg-gray-50 rounded-lg border border-gray-300 focus:ring-blue-500 focus:border-blue-500"
            placeholder="Ketik isi laporan anda..."></textarea>
        </div>
        <div>
          <label for="first_name" class="block mb-1 text-sm font-medium text-gray-900 ">Terlapor</label>
          <input type="text" id="first_name"
            class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5"
            placeholder="John" required />
        </div>


        <div>
          <label for="countries" class="block mb-2 text-sm font-medium text-gray-900 ">Pelapor</label>
          <select id="countries"
            class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5">
            <taption selected>Pilih daa</taption>
            <option value="">Korban</option>
            <option value="">Keluarga Korban</option>
            <option value="">Saksi</option>
            <option value="">Masyarakat</option>
          </select>
        </div>
        <div>
          <label for="countries" class="block mb-2 text-sm font-medium text-gray-900 ">Kategori Aduan</label>
          <select id="countries"
            class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5">
            <option selected>Pilih Kategroi</option>
            <option value="">Korupsi</option>
            <option value="">Narkotika</option>
            <option value="">Teroris</option>
            <option value="">Pencucian Uang</option>
          </select>
        </div>



        <div>
          <button class="px-3 py-2 bg-green-700 rounded-sm text-white">LAPOR!</button>
        </div>

      </div>
    </div>
  </div>
</template>