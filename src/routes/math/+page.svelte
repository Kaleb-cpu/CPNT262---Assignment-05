<script>
  import { browser } from '$app/environment'


  let hobbyOne = [];
  let hobbyTwo = [];
  let hobbyThree = [];

  if (browser){
    for (let i = hobbyOne; i<=hobbyThree; i++) {
      hobbyOne = [prompt('What is your favourtie hobby?')]
      hobbyTwo = [prompt('What is your second favourtie hobby?')]
      hobbyThree = [prompt('What is your third favourtie hobby?')]

    hobbyOne.push(i);
    hobbyTwo.push(i);
    hobbyThree.push(i);
}
  }
</script>

<p>{hobbyOne}</p>
<p>{hobbyTwo}</p>
<p>{hobbyThree}</p>