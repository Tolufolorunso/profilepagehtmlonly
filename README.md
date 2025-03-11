---

## HTML Structure
### 1. **Header**
- Displays the profile title.
- Includes a navigation menu with links to:
  - About Us
  - Hobbies
  - Contact

### 2. **Main Content**
#### a. About Section (`#about`)
- Contains placeholder text.
- Includes an image placeholder.

#### b. Hobbies Section (`#hobbies`)
- Lists personal hobbies:
  - Reading
  - Coding
  - Playing
  - Game

#### c. Contact Section (`#contact`)
- Displays a phone number.

### 3. **Footer**
- Provides a social media link (X: `@developer_tolu`).

---

# Code Sample

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Personal Profile Page</title>
  </head>
  <body>
    <header>
      <p>My Profile</p>
      <ul>
        <li><a href="#about">About Us</a></li>
        <li><a href="#hobbies">Hobbies</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </header>
    <main>
      <section id="about">
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam
          officiis ut eum velit assumenda tempore ea, culpa deleniti
          exercitationem a suscipit laborum quae aliquid doloribus rem nam earum
          iste ipsam.
        </p>
        <img src="" alt="Placeholder" />
      </section>
      <section id="hobbies">
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi debitis
          eum ex consequuntur nostrum aperiam, consectetur optio minus? Sit,
          maxime?
        </p>
        <ul>
          <li>Reading</li>
          <li>Coding</li>
          <li>Playing</li>
          <li>Game</li>
        </ul>
      </section>
      <section id="contact">
        <p>Contact: 08068callme</p>
      </section>
    </main>
    <footer>
      <p>you will find me X: @developer_tolu</p>
    </footer>
  </body>
</html>
```
