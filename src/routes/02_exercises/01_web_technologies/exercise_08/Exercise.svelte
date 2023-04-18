<script>
    const my_name = 'Heather'
    const fav_things = ['my dog', 'embroidery', 'crochet']
</script>


My name is {my_name} and these are some of my favourite things: 
    <ul>
        {#each fav_things as thing}
        <li>{thing}</li>
        {/each}
    </ul>
