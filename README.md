# Extraer subtitulos de flow

https://linkdeprueba.com/nPVR/c3eds/261_AMC_T_202305160200-202305160300_ON_Anevia3/SA_Live_dash_enc/AMC.mpd
↓

cambiar SA_Live_dash_enc por SA_MOBILE y mpd por m3u8

https://linkdeprueba.com/nPVR/c3eds/261_AMC_T_202305160200-202305160300_ON_Anevia3/SA_MOBILE/AMC.m3u8

Descargalo con yt-dlp con este comando

yt-dlp --skip-download --allow-unplayable-formats --write-subs --sub-langs all --sub-format vtt "https://linkdeprueba.com/nPVR/c3eds/261_AMC_T_202305160200-202305160300_ON_Anevia3/SA_MOBILE/AMC.m3u8"

Corregir los subtitulo con subtitle edit y borrar esta lineas con reemplazo múltiple 

<c.white.bg_transparent></c>
<c.white.bg_transparent><font color="white">
</font></c>
</font>
<font color="white">
  
Bueno te toca sincronizar y arreglar algunas lineas
ejemplo:
  
¡Poraquñ
//////////
¿Hol ? '
a. ¿Hay alguien ahí?
//////////
- ¡Atrás' '
. ¡Atrá
- ¡No! S!
//////////
Tienen a Mo. ¿A quién más
fienen?
//////////
; De dónde,dja,bjgs sacan oaso!ina?
//////////
Ios entregaron voluntariamente
por una vida mejor.
//////////
