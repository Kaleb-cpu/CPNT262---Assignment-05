<script>
  import { browser } from '$app/environment'


  let name = [];
  let age = [];
  let hobby = [];
  // let text = name.join(" and ");

  if (browser){
    for (let i = name; i<=hobby; i++) {
      name = [prompt('What is your Name?')]
      age = [prompt('How old are you?')]
      hobby = [prompt('What is your favourtie hobby?')]

    name.push(i);
    age.push(i);
    hobby.push(i);
}
  }

  console.log(name + age + hobby)
</script>

<p>{name}{age}{hobby}</p>