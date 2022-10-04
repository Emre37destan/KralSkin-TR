<div align="center">

[![C++](https://img.shields.io/badge/Language-C%2B%2B-%23f34b7d.svg?style=plastic)](https://en.wikipedia.org/wiki/C%2B%2B)
[![LOL](https://img.shields.io/badge/Game-League%20of%20Legends-445fa5.svg?style=plastic)](https://na.leagueoflegends.com)
[![Windows](https://img.shields.io/badge/Platform-Windows-0078d7.svg?style=plastic)](https://en.wikipedia.org/wiki/Microsoft_Windows)
[![x86](https://img.shields.io/badge/Arch-x86-red.svg?style=plastic)](https://en.wikipedia.org/wiki/X86)
[![License](https://img.shields.io/github/license/Emre37destan/KralSkin-TR.svg?style=plastic)](LICENSE)
[![Issues](https://img.shields.io/github/issues/Emre37destan/KralSkin-TR.svg?style=plastic)](https://github.com/Emre37destan/KralSkin-TR/issues)
![Windows](https://github.com/Emre37destan/KralSkin-TR/workflows/Windows/badge.svg?branch=main&event=push)
# **KralSkin-TR**
<img src="https://raw.githubusercontent.com/Emre37destan/KralSkin-TR/main/KralSkin-TRR.png">
</div>

`KralSkin-TR`, League of Legends için dahili görünüm değiştiricidir.
- Oyundaki şampiyonunuzun ve diğer şampiyonların görünümünü değiştirin.
- Otomatik kaplamalar veritabanı güncellemesi.
- Seyirci modu için destek.
- Tek bir oyunda kaplamaları istediğiniz zaman ve sınırsız kez değiştirin.
- Dünyadaki tüm Popüler dilleri  ​​destekler.
- <a href="https://github.com/ocornut/imgui">ImGui</a> ile oyun içi yapılandırma.
- <a href="https://github.com/nlohmann/json">JSON</a> tabanlı yapılandırma kaydetme ve yükleme

# Bina
1. Kaynağı `git clone --recursive https://github.com/Emre37destan/KralSkin-TR.git` ile klonlayın
2. "Bölgeniz" yapılandırmasıyla Visual Studio 2017/19'da oluşturun

# Kullanım
1. `KralSkin_Enjektor` kullanın veya ortaya çıkan DLL'yi oyuna kendiniz enjekte edin.
   - Enjekte başarısız olursa *Yönetici* ayrıcalığı gerekebilir.
   - Lig istemcisi, arenaya girmeden önce enjekte edilirse çökebilir.
      - Bir geçici çözüm, arenada olana kadar enjeksiyon yapmamaktır (oyunu bozmamak için hızlı olmanız gerekir).
2. Menüyü getirmek için <kbd>Ekle</kbd>'ye basın.
3. Kendiniz, takım arkadaşlarınız, düşmanlarınız, totemleriniz için görünüm seçin.

# Diğer optimizasyonlar
CPU'nuz AVX / AVX2 / AVX-512 komut setini destekliyorsa proje ayarlarından etkinleştirebilirsiniz. Bu, CPU'nuz için optimize edilmiş daha performanslı kodla sonuçlanmalıdır.

# Kredi
Bu program, <a href="https://github.com/R3nzTheCodeGOD">B3akers'in</a>/<a href="https://github.com/R3nzTheCodeGOD/R3nzSkin">LeagueSkinChanger</a> geliştirilmiş ve güncellenmiş bir sürümüdür.
