<script context='module'>
export async function load({ page }) {

    return {
        props: {
            comma: page.query.get('comma'),
            simple: page.query.get('simple'),
        },
        status: 200,
    }
}
</script>
<script>
  export let comma, simple
</script>

Comma query parameter:
{comma}
<br/>
Simple query parameter:
{simple}
