# FCAI
Pyplot почему-то захотел выводить изображения в BGR после конвертации в полутон

Фиксится через cv2.cvtColor(np.asarray(imgorig), cv2.COLOR_BGR2RGB)

Без предварительного преобразования Image.fromarray(uint8(brg_im)) может не заработать (из-за канальности)
