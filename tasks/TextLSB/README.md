TextLSB
=======

>Отдел раздведки смог достать переписку одного из агентов противника. К 
>несчастью, на нашего ведущего специалиста по крипто- и стего-анализу было
>соверщено покушение. Мы думаем, это может быть свзянано тем, что содержится
>в этом сообщении. Нам нужна твоя помощь, чтобы расшифровать его.

-----------------------------------------------------------------------------

Flag
QCTF_6590c99538be6f02936286ed716bb050

------------------------------------------------------------------------------

Описание

Участникам выдается текст, в котором зашифрован флаг. Необходимо взять остаток
деления по модулю 2 от каждого кода символа, которые образуют битовую строку кратности 8. Собирая в блоги по 8 бит, и перводя в байты, получается строка флага.

==================================================================================

Файлы
user/strange.txt - Текст, в котором зашит флаг, выдается участнику.
ravegen.py - бредогенератор контейнера (текста) для необходимой стего-строки
words.txt - словарь для бредогенератора
example_solution.py - пример решения для извлечения стего-строки из текста на языке Python
textlsb.py - графический интерфейс для генерации стего-строк