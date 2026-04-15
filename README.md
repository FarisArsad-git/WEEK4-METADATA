# WEEK 4 - METADATA

| Picture        | Tools             | Link / Command       | POC  | Analysis |
|----------------|-------------------|----------------------|------|----------|
| Ocean.jpg      | exiftool          | https://exif.tools/  |  | Online tools can also output same result as command in Kali          |
|                |                   | `exiftool ocean.jpg` |<img width="662" height="831" alt="image" src="https://github.com/user-attachments/assets/62c6ddaf-abcb-4ad9-b33d-f4086d9711f5" />| Can clearly saw the flag in comment section      |
| Computer.jpg   | Hexeditor         | https://hexed.it/    | | Analyse the docs header      |
|                |                   | `hexeditor computer.jpg` |<img width="647" height="238" alt="image" src="https://github.com/user-attachments/assets/a1c0453d-2bdd-4fde-aaf9-e039ad7f0c8b" />| Hexeditor in kali is really easy to use. <br> Can refer here for the header https://filesig.search.org/ |
| dog.jpg        | binwalk           | `binwalk dog.jpg` <br> `binwalk -e dog.jpg` <br> `cd _dog.jpg.extracted/` |<img width="772" height="661" alt="image" src="https://github.com/user-attachments/assets/9c821ce6-dc02-4e6d-a58b-5d25393ca00d" /> | `binwalk` usually use for finding hidden file in the main file  |
| computer.jpg   | strings           | https://www.dcode.fr/strings-extractor | | online tools for command `strings` |
|                |                   | `strings computer.jpg`|<img width="472" height="395" alt="image" src="https://github.com/user-attachments/assets/1c5f78f4-0040-4090-ad52-dee65876837b" />| used to extract human-readable text from files, especially binary files.          |
| solitaire.exe  | file | `file solitaire.exe` |<img width="650" height="71" alt="image" src="https://github.com/user-attachments/assets/6a8e9065-8bab-4b06-8c26-f94859bdd2b9" />| solitare.exe is actually a PNG file |
| rubiks.jpg     | file | `file rubiks.jpg`    |<img width="647" height="76" alt="image" src="https://github.com/user-attachments/assets/555bdb64-d21a-445f-86a6-152e2bb9e993" />| After checking the jpg file is actually a png |
