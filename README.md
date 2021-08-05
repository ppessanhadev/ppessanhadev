### Hi there <img src="https://camo.githubusercontent.com/e8e7b06ecf583bc040eb60e44eb5b8e0ecc5421320a92929ce21522dbc34c891/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f6876524a434c467a6361737252346961377a2f67697068792e676966" width="30" heigth="30" />

Olá! Meu nome é Pablo, sou um desenvolver Full Stack apaixonado pelo o que faço, interessado sempre em evoluir e aprender cada vez mais, e também em repassar adiante todo meu conhecimento.

Atualmente estou cursando **Trybe**, onde eu pude ter o privilegio de adquirir todo o meu conhecimento de Frontend e Backend(com a linguagem Javascript), e encontrando a certeza da minha paixão por esse vasto mundo da programação. <3

Durante a minha trajetória até então, sempre encarei muitos desafios, muitas vezes achava que mal ia conseguir, mas, com bastante força de vontade e de adquirir conhecimento, sempre consegui superar todas elas e atingir o resultado que gostaria. :)

#### Descubra um pouco mais sobre meus conhecimentos/interesses lendo o código abaixo:
```js
class AboutMe {
  constructor() {
    this.fullName = 'Pablo Pessanha';
    this.birthday = new Date('06/24/1997');
    this.employment = 'Backend developer';
    this.worksAt = 'Tasken';
    this.email = 'pablopessanh@gmail.com';
    this.skills = {
      languages: ['Javascript', 'Typescript', 'Python', 'Shell Script'],
      backend: ['NodeJS', 'Express', 'NestJS'],
      frontend: ['HTML5', 'CSS3', 'SCSS', 'ReactJS'],
      databases: ['MySQL', 'SQL Server', 'Postgres', 'MongoDB'],
      tools: {
        versionControl: ['Git', 'GitHub'],
        tests: ['Jest', 'React Testing Library'],
        containers: ['Docker'],
        cloud: ['Heroku'],
        ORM: ['Sequelize', 'TypeORM'],
      },
    }
  };
    
  learningLanguages() {
    this.skills.languages.push('Java');
  }
  
  learningFrameworks() {
    this.skills.backend.push('Spring Boot');
    this.skills.frontend.push('Angular');
  }
  
  lookingAt() {
    this.lookingAt.languages = ['GoLang', 'Ruby', 'Elixir'];
    this.lookingAt.tools.cloud = ['AWS', 'Digital Ocean'];
    this.lookingAt.tools.containers = ['Docker Compose', 'Kubernetes']
  }
}
```