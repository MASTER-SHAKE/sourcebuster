install js, and add follow scripts

<script type="text/javascript" src="js/sourcebuster.min.js"></script>







<script>
    function doSmth(sb) {
        $('.referer').val(sbjs.get.current.typ);
        $('.transition').val(sbjs.get.current.src);
        $('.canal').val(sbjs.get.current.mdm);
        $('.campaign').val(sbjs.get.current.cmp);
        $('.content').val(sbjs.get.current.cnt);
        $('.keywords').val(sbjs.get.current.trm);
        $('.point').val(sbjs.get.current_add.ep);
        $('.last_referer').val(sbjs.get.current_add.rf);
    }
</script>


<script>
    sbjs.init({
        domain: 'domain.ru',
        lifetime: 3,
        callback: doSmth
    });
</script>