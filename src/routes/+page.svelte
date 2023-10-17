<script lang="ts">
    import { enhance } from '$app/forms';
    import type { PageData } from './$types';
    
    export let data: PageData;
</script>


<h1>
    HOME
</h1>

<form method="post" action="/login?/logout" use:enhance>

    <button>LOGOUT</button>

</form>

<h2><a href="http://localhost:5174/sessions">Sessions</a></h2>