# joinUs()
A different way to hire you 💻🤓😍🍺

## How to apply?

- 🍴Fork this repository.
- 💻Go to your favorite terminal and clone your forked repo 
- 💪Check `skills.yaml` and then choose the main skill that defines you much better the rest. I should say the skill that you can burn more story points 🤪 anyway don't worry within the next step you can add more skills, but here just pick up the main one!
- 🥨Checkout to the branch relevant to your skill. For each skill I have created a branch like `skill/reactjs`.
- 🍔Create a **YAML** file and name it `<YOUR GITHUB ID>.me.yaml` and add following information about yourself;
  - `nickname (string)`: A string value that point to whatever you like us to call you.
  - `email (string)`: Your email address.
  - `skills (string[])`: A list of other skills that you can burn some story points (choose from skills.yaml).
  - `slack (string)`: your slack id.
  - `description (string)`: Describe yourself in anyway you like.
- 🍤use `openssl` and encrypt your `<YOUR GITHUB ID>.me.yaml` file with the public key that you can find it in the root folder of the `master` branch. It's name is `public.pem` and for the encryptes file use this name `<YOUR GITHUB ID>.me.yaml.encrypted`. Fyi the given key is a 2048 bit rsa key, andI expect you know how to generate it and use it to encrypt a text file.
  - Just to make sure I can decrypt your file, plz test it before you send, you can test it like this:
    - `openssl rsautl -decrypt -inkey private.pem -in <YOUR GITHUB ID>.me.yaml.encrypted -out <YOUR GITHUB ID>.me.yaml.txt`
- 🍿remove the origin file otherwise everyone will see your information. 
- 🍺push all changes to your repository and make a pull request to this repo and for your selected skill branch. 
  - ⚠️ Make sure to follow `YUORNAME's application is done` in your pull request commit message.
- 🥂My github action will do the rest.

Happy branching 🤓
