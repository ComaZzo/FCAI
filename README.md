# FCAI
Pyplot почему-то захотел выводить изображения в BGR после конвертации в полутон

Фиксится для трехканальных изображений через cv2.cvtColor(np.asarray(imgorig), cv2.COLOR_BGR2RGB)

Image.fromarray(uint8(brg_im)) не поможет, изображение искажается
