---
title: 'ปัตตะโชติ #3 – ดึงชุดคำจาก Libthai ด้วย Elixir'
author: narze

date: 2016-11-29T17:49:40+00:00
url: /learn/ปัตตะโชติ-3-libthai-elixir/
featuredImage: /images/cover/pattachote-3-libthai-elixir.png
categories:
  - Learn
tags:
  - geek
  - pattachote

---
บันทึกการใช้ Layout ปัตตะโชติ เมื่อผ่านมาแล้ว 2 อาทิตย์ ยังมีปัญหาจำตัวอักษรได้ไม่หมด โดยเฉพาะตัวที่ไม่ได้ใช้บ่อย และพวกที่ต้องกดพร้อมกับ Shift ยิ่งแทบจำไม่ได้ เลยยังต้องเก็บโพยปัตตะโชติเอาไว้อยู่

ที่พิมพ์ได้คล่องแล้วคือ Home row ที่เอาชุดคำไปขึ้นในเว็บ [10fastfingers][1] แต่พอเริ่มขยายไปแถวอื่นๆ ก็นึกคำที่จะใช้ฝึกได้ไม่ครอบคลุมแล้ว เพราะคำยิ่งเยอะ Combination ก็จะยิ่งเยอะตามไปด้วย

เนื่องจากที่ช่วงนี้กำลังลองเล่นภาษา Elixir ก็เลยทดลองเขียน[โปรแกรม Generate คำ][2] ที่ประกอบด้วยตัวอักษรที่กำหนดให้ออกมา เช่นถ้าใส่ตัวอักษร `ท,ง,ก,า,น,เ` เข้าไป จะได้คำภาษาไทยออกมา เป็น `กางเกง,งก,ทนง,ทนทาน,นาง,เทา` เป็นต้น โดยชุดคำที่นำมาใช้เอามาจาก [Libthai][3] ครับ

Blog นี้ใช้เวลาพิมพ์และเรียบเรียงประมาณ 15 นาที นับว่าเร็วขึ้นมาหน่อย

 [1]: https://10fastfingers.com/text/85665-Pattachote-Home-Row-ท-ง-ก-า-น-เ-ไ-ข
 [2]: https://gist.github.com/narze/942ddbeaada619c7e3a91f1af7a741ca
 [3]: https://github.com/tlwg/libthai/tree/master/data
