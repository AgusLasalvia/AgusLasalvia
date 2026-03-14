```javascript

class Developer {
  constructor({
    name,
    age,
    languages,
    role,
    university,
    email,
    linkedin,
    instagram,
    status
  }) {
    this.name = name
    this.age = age
    this.languages = languages
    this.role = role
    this.university = university
    this.email = email
    this.linkedin = linkedin
    this.instagram = instagram
    this.status = status
  }

  greet() {
    console.log("Hello There! :)")
  }
}

const agustin = new Developer({
  name: "Agustin Lasalvia",
  age: 24,
  languages: ["Spanish", "English"],
  role: "Junior Developer",
  university: "ORT University",
  email: "agus.blumenfeld13@gmail.com",
  linkedin: "https://www.linkedin.com/in/agustin-lasalvia",
  instagram: "https://www.instagram.com/agustin.lasalvia",
  status: "Searching for a Junior Developer Position"
})

agustin.greet()
