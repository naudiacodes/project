<html>
  <head>
    <style>
      h1 {
        text-align: center;
        color: blueviolet;
      }

      h2 {
        text-align: center;
        border-radius: 10px;
        border: 1px solid blueviolet;
        padding: 15px;
      }

      img {
        border-radius: 10px;
        width: 100%;
      }

      p {
        font-size: 14px;
        line-height: 1.5;
      }

      button {
        width: 100%;
        background: blueviolet;
        color: white;
        border: none;
        padding: 15px;
        font-size: 20px;
        border-radius: 30px;
        box-shadow: 0 15px 20px rgba(0, 0, 0, 0.3);
        margin: 20px 0;
      }

      footer {
        text-align: center;
        font-size: 12px;
      }
    </style>
  </head>
  <body>
    <h1>
      🧘‍♀️ Yoga
    </h1>
    <h2>
      Discipline
    </h2>
    <img
      src="https://static01.nyt.com/images/2016/12/02/well/move/yoga_body_images-slide-HNVD/yoga_body_images-slide-HNVD-blog480.jpg"
      alt=""
    />
    <p>
      Yoga is a group of physical, mental, and spiritual practices or
      disciplines which originated in ancient India. Yoga is one of the six
      Āstika schools of Hindu philosophical traditions. There is a broad variety
      of yoga schools, practices, and goals in Hinduism, Buddhism, and Jainism.
      <br />
      <br />
      <a href="https://en.wikipedia.org/wiki/Yoga">
        Learn more on Wikipedia
      </a>
    </p>
    <button>
      Go to a Yoga class
    </button>
    <footer>
      Coded by 👩‍💻
      <a href="https://www.shecodes.io">
        SheCodes
      </a>
    </footer>

    <script>
      function subscribe() {
        let name = prompt("What is your name?");
        prompt("What is your email address?");

        alert(
          `Thanks, ${name}! We'll be in touch! Meanwhile, don't forget to breathe 🧘‍♀️`
        );
      }

      let button = document.querySelector("button");
      button.addEventListener("click", subscribe);
    </script>
  </body>
</html>
