<h1 align="center">
  <img alt="GoStack" src="./assets/gostack.png">
</h1>

<p align="center">
  <img alt="Last commit on GitHub" src="https://img.shields.io/github/last-commit/tavareshenrique/nodejs-gostack11?color=7D40E7">
  <img alt="Made by Henrique Tavares" src="https://img.shields.io/badge/made%20by-Henrique Tavares-%20?color=7D40E7">
  <img alt="Project top programing language" src="https://img.shields.io/github/languages/top/tavareshenrique/nodejs-gostack11?color=7D40E7">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/tavareshenrique/nodejs-gostack11?color=7D40E7">
  <img alt="GitHub license" src="https://img.shields.io/github/license/tavareshenrique/nodejs-gostack11?color=7D40E7">
</p>

<p align="center">
  <a href="#information_source-content">ℹ️ Conteúdo</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-technologies">🚀 Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-author">💻 Autor</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">📝 Licença</a>
</p>

<p align="center">
  Esse projeto foi desenvolvido para o estudo de Node com TypeScript no Bootcamp GoStack 11 da Rocketseat.
</p>

---

# :information_source: Conteúdo

- [Appointments](#appointments)
  - [List All](#list-all-appointments)
  - [Create](#create-appointments)

---

# Appointments

## **List All** Appointments

ListAll Appointments.

* **URL**

  `/appointments`

* **Method:**

  `GET`

* **URL Params**

   **Required:**

    None

    **Optional:**

* **Data Params**

  None

* **Success Response:**

  * **Code:** 200 <br />
    **Content:**

    ```json
    [
      {
        "id": "09799b3c-8486-4334-b9ff-d061e2419266",
        "provider": "Henrique",
        "date": "2020-05-30T20:00:00.000Z"
      }
    ]
    ```

---

## **Create** Appointments

Create a Appointment.

* **URL**

  `/appointments`

* **Method:**

  `POST`

* **URL Params**

   **Required:**

    None

* **Data Params**

    ```json
    {
      "provider": "Henrique",
      "date": "2020-05-30 21:00:00"
    }
    ```

* **Success Response:**

  * **Code:** 200 <br />
    **Content:**

    ```json
    {
      "id": "99c8cb07-f3dc-42b5-9418-11eaafe3bf75",
      "provider": "Henrique",
      "date": "2020-05-31T00:00:00.000Z"
    }
    ```

---

# :rocket: Tecnologias

- [TypeScript](https://www.typescriptlang.org/)
- [ts-node-dev](https://github.com/whitecolor/ts-node-dev)
- [express](https://expressjs.com/pt-br/)
- [date-fns](https://date-fns.org/)
- [uuidv4](https://github.com/thenativeweb/uuidv4#readme)
- [eslint](https://eslint.org/)
- [prettier](https://prettier.io/)

---

# :computer: Autor

<table>
  <tr>
    <td align="center">
      <a href="http://github.com/tavareshenrique/">
        <img src="https://avatars1.githubusercontent.com/u/27022914?v=4" width="100px;" alt="Henrique Tavares"/>
        <br />
        <sub>
          <b>Henrique Tavares</b>
        </sub>
       </a>
       <br />
       <a href="https://www.linkedin.com/in/tavareshenrique/" title="Linkedin">@tavareshenrique</a>
       <br />
       <a href="https://github.com/tavareshenrique/nodejs-gostack11/commits?author=tavareshenrique" title="Code">💻</a>
    </td>
  </tr>
</table>

---

# :memo: License

This project is licensed under the MIT license - see the archive [LICENSE.md](https://github.com/tavareshenrique/nodejs-gostack11/blob/master/LICENSE.md) for details.
