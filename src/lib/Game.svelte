<script>
// @ts-nocheck

     import { onMount } from 'svelte';

    function init(){
        let stage = new createjs.Stage('game');

        let circle = new createjs.Shape();
        circle.graphics.beginFill("red").drawCircle(0, 0, 40);
        circle.x = circle.y = 50;
        stage.addChild(circle);
        stage.update();
    }

    onMount(() => {
        init();
    });
</script>

<canvas class="border border-primary p-2 m-2" width="700" height="500" id="game"></canvas>