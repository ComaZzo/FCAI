# FCAI
Pyplot почему-то захотел выводить изображения в BRG после конвертации в полутон

Фиксится через cv2.cvtColor(imgorig, cv2.COLOR_BGR2RGB)
