# ExamY Backend Deploy

## π ExamY μκ°

- μ¨λΌμΈ μν κ°λ μλΉμ€ μ κ³΅μ μν `μν μ μ`, `μλ λΆμ νμλ₯Ό κ°μ§`νλ μΉ μ΄νλ¦¬μΌμ΄μμλλ€.
- μν μ μ : κ΄λ¦¬μλ μν λ¬Έμ μ§μ μ μν  μ μκ³ , μνμ κ°μ€ν  μ μμ΅λλ€.
- μλ λΆμ νμ κ°μ§ : Pre-trained λͺ¨λΈμ νμ©νμ¬ μ¬μ©μμ λΆμ νμλ₯Ό μλ κ°μ§ν  μ μμ΅λλ€.

## π¨ κΈ°μ  μ€ν

<p align='center'>
    <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white"/>
     <img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge"/>
      <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
    <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white"/>
    <img src="https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white"/>
</p>

## π νλ‘μ νΈ μν€νμ²

![image](https://user-images.githubusercontent.com/48426909/134015147-dbef766c-48f6-4f5a-a39f-7b913c8c2a21.png)

### API URI

| λ²νΈ | μ ν | URI                         | μ€λͺ                                                |
| :--- | :--- | :-------------------------- | :-------------------------------------------------- |
| 1    | POST | /api/users/login            | μλ ₯ν μ΄λ©μΌ&λΉλ°λ²νΈλ₯Ό κΈ°μ€μΌλ‘ λ‘κ·ΈμΈ μμ²­       |
| 2    | GET  | /api/users/logout           | νμ¬ λ‘κ·ΈμΈ λ μ μ λ₯Ό λ‘κ·Έμμ μμ²­                 |
| 3    | POST | /api/users/register         | μ μ  μ λ³΄λ₯Ό κΈ°λ°μΌλ‘ νμκ°μ μμ²­                  |
| 4    | GET  | /api/users/auth             | μ§κΈ λ‘κ·ΈμΈλ νμ¬ μ μ μ μΈμ¦ μ λ³΄λ₯Ό μμ²­          |
| 5    | POST | /api/users/upload/userimage | μ μ μ μΌκ΅΄ μ΄λ―Έμ§λ₯Ό λ°λ‘ DBμ μ μ₯ μμ²­            |
| 6    | POST | /api/test/upload/question   | κ΄λ¦¬μκ° μ μν λ¬Έμ λ€ DBμ μ μ₯ μμ²­               |
| 7    | POST | /api/test/maketest          | μ μλ λ¬Έμ λ€μ λ°νμΌλ‘ DBμ μν μ λ³΄λ₯Ό μ μ₯ μμ²­ |
| 8    | POST | /api/room/fetch/exam        | Exam Codeλ₯Ό κΈ°μ€μΌλ‘ μνμ μ λ³΄λ€μ κ°μ Έμ€λ μμ²­  |
| 9    | POST | /api/room/fetch/questions   | Exam Codeλ₯Ό κΈ°μ€μΌλ‘ μνμ λ¬Έμ λ€μ κ°μ Έμ€λ μμ²­  |

### μμλ΄μ­

- π 2020 κ΅λ΄ μννΈμ¨μ΄νλΆ κ³΅λͺ¨μ  κΈμ μμ

### κΈ°νμ¬ν­

- νμ¬ heroku, mongoDB μ°λ λ¬Έμ λ‘ μΈν΄ μ€μ  λ°λͺ¨λ μλνμ§ μλ μ΄μκ° μμ΅λλ€.
- [λ°λͺ¨μμ](https://www.youtube.com/watch?v=8XiyuhnKvyE)
