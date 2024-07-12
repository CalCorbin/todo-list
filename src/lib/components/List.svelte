<script>
    let listItems = [
        { id: 1, text: "Item 1" },
        { id: 2, text: "Item 2" },
        { id: 3, text: "Item 3" },
        { id: 4, text: "Item 4" }
    ];
</script>
<ul>
    {#each listItems as item}
        <div class="listItemRow">
            <li><input type="checkbox">{item.text}</li>
        </div>
    {/each}
</ul>
<style>
    .listItemRow {
        display: flex;
        align-items: center;
        list-style-type: none;
        margin: 0;
        padding: 0;
    }
</style>