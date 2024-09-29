```typescript
interface Profile {
  name: string;
  role: string;
  age: string;
  experience: string;
  education: {
    school: string;
    jurusan: string;
  };
}

function introduceMySelf(profile: Profile): string {
  const intro = `Hi, my name is ${profile.name}. I am a ${profile.role}.`;
  const details = `I am ${profile.age} years old with ${profile.experience} of experience.`;
  const edu = `I studied ${profile.education.jurusan} at ${profile.education.school}.`;
  return `${intro}\n${details}\n${edu}`;
}

const developer: Profile = {
  name: "Reza Adi",
  role: "Frontend Developer",
  age: "16 years old",
  experience: "2 months",
  education: {
    school: "SMK Negeri 5 Surakarta",
    jurusan: "PPLG (Pengembangan Perangkat Lunak dan Gim)"
  }
};

console.log(introduceMySelf(developer));
```

<p align="left">
  <samp>
    <a href="https://ryznoxy.my.id" target='_blank'>website & portfolio</a>
  </samp>
</p>

[![Mail Badge](https://img.shields.io/badge/-@r7zaa_-e84393?style=flat&labelColor=e84393&logo=instagram&logoColor=white)](https://instagram.com/r7zaa_) 
[![Mail Badge](https://img.shields.io/badge/-rezaanreza27@gmail.com-c0392b?style=flat&labelColor=c0392b&logo=gmail&logoColor=white)](mailto:rezaanreza27@gmail.com)
[![](https://komarev.com/ghpvc/?username=ryznoxy&color=blue&label=Profile%20Views)](https://github.com/ryznoxy)
[![](https://img.shields.io/github/followers/ryznoxy?label=GitHub%20Followers)](https://github.com/ryznoxy)
<br />



