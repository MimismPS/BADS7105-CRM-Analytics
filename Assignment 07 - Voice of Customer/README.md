# Voice of Customer Analytics

[![](https://img.shields.io/badge/-NLP-brightgreen)](#) [![](https://img.shields.io/badge/-K--Means-brightgreen)](#) [![](https://img.shields.io/badge/-Python-brightgreen)](#) [![](https://img.shields.io/badge/-Google--Colab-brightgreen)](#) 


**Google Colab:** [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1qQgZAIfuGNZrRrmOiQIY9wOrpj0y0-5C)

## Dataset
"Wongnai Reviews - Small"

## Clustering using K-Means

<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2007%20-%20Voice%20of%20Customer/No.%20of%20cluster.png" />
Four clusters you see fit the most.


<hr>

## Define words to remove as well as new words for tokenization
</p>
Removed words --> "u", "b", "n", "nn", "nn-", "\n", "ร้าน", "กก", "ดิชั้น", "ดังนั้น", "ตั้งอยู่", "ลอง", 
              "['", "ดิ", "tamp", "น", "ซอย", "ร้า", "ลอง", "ชั้น", "เจอ", "คน", "นั่ง",
              "นึง", "อ", "ไหม", "วัง", "พันธุ์", "เวลา", "โมง", "สันทัด", "ดังนั้น", "เฉพาะเรื่อง",
              "nTamp", "สั่ง", "(", ")", "]", "-", "ช้ัน" , "ทบ", "โถม", "เลือก", "review","แก้",
              "ร่างกาย", "รอบ", "ย้ำ", "มีผลต่อ", "ช๊อต", "บาท", "พี่", "เรื่อง"
</p> 
Add new words --> "สตารบัก", "แบล๊กแคนยอน", "ช๊อคโกแล๊ต", "ช้อคโกแลต", "คาเฟ่", "โฮมเมด", "สมูตตี้", "แม่ศรีเรือน", 
              "ยำแซ่บ", "อีสาน", "คาปู", "อิตาเลี่ยนโซดา", "บาริสต้า", "ดาร์คช๊อก", "ชานมไข่มุก", "เมล็ดกาแฟ"

<hr>

## Result
</p> 

<i><ins>Cluster 1: "Enjoy Eating"</i></ins>

ลูกค้ากลุ่มนี้มักรีวิวว่าได้ทานอาหารที่มีรสชาติอร่อย กาแฟรสชาติดี ราคาก็ดี โดยรวมชื่นชอบ มีความประทับใจ ดังนั้นควรรักษามาตรฐานเดิมของร้านในทุกๆด้าน

<i><ins>Cluster 2: "Enjoy Watermelon"</i></ins>

ลูกค้ากลุ่มนี้มักรีวิวว่าได้ดื่มน้ำแตงโมปั่นที่มีรสชาติดี แต่เมล็ดเยอะไปหน่อย ดังนั้นควรเอาเมล็ดออกให้หมดก่อนนำไปปั่น ลูกค้าจะได้เกิดความพึงพอใจ

<i><ins>Cluster 3: "Dislike Service"</i></ins>

ลูกค้ากลุ่มนี้ได้ไปรับประทานอาหารที่ร้านแม่ศรีเรือน สาขาโฮมโปร ซึ่งพนักงานบริการแย่มาก ดังนั้นร้านควรปรับปรุงการให้บริการให้ดียิ่งขึ้น พนักงานควรมีใจรักบริการมากกว่านี้

<i><ins>Cluster 4: "Dislike Texture"</i></ins>

ลูกค้ากลุ่มนี้มักซื้อนมและกาแฟมาทาน แต่ร้านที่ซื้อรสชาติไม่โอเค ไม่เข้มข้น ไม่มากเกินไปก็น้อยเกินไป ดังนั้นร้านควรปรับปรุงรสชาติให้มีเอกลักษณ์และทำให้อร่อยกว่านี้
