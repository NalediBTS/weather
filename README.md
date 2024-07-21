<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Homework</title>
    <style>
      h1 {
        color: #1a64d6;
        font-size: 38px;
        line-height: 48px;
        font-weight: bold;
        text-align: center;
        margin: 0;
      }

      p {
        text-align: center;
        font-family: monospace;
        opacity: 0.7;
        font-size: 18px;
      }

      h2 {
        text-align: center;
        margin: 0;
        font-weight: 300;
        font-size: 36px;
        line-height: 46px;
      }

      ul {
        list-style: none;
        padding: 0;
        text-align: center;
      }

      button {
        margin: 20px auto;
        display: block;
        color: #1a64d6;
        font-size: 16px;
        background: transparent;
        padding: 15px 20px;
        border: 1px solid #1a64d6;
        border-radius: 30px;
        box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.3);
        transition: all 200ms ease-in-out;
      }

      button:hover {
        background: #1a64d6;
        color: white;
        cursor: pointer;
        border: 1px solid #1a64d6;
      }

      li {
        list-style: none;
        text-align: center;
        padding: 9px 0;
        border-radius: 9px;
        transition: all 180ms ease-in-out;
        max-width: 300px;
        margin: 0 auto;
      }

      li:hover {
        background: #fffbef;
        color: black;
        cursor: pointer;
      }
    </style>
  </head>
  <body>
    <h1>
      ⛅ <br />
      <strong>Currently 21&deg; in Tokyo</strong>
    </h1>
    <h2>
      13&deg; /
      <strong>23&deg;</strong>
    </h2>

    <ul>
      <li>
        <h3>🌧Tomorrow</h3>
        <p>10&deg; / <strong>22&deg;</strong></p>
      </li>

      <li>
        <h3>🌤Saturday</h3>
        <p>15&deg; / <strong>17&deg</strong></p>
      </li>

      <li>
        <h3>🌞Sunday</h3>
        <p>25&deg; / <strong>28&deg;</strong></p>
      </li>
    </ul>

    <button>Change City</button>
    <p>Coded by Nakedi Makgakga</p>
  </body>
</html>
