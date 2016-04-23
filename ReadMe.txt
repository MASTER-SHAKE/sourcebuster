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


--------------  JOOMLA -----------------------

<tr class="rsform-block rsform-block-referer hidden">
    <td>{referer:caption}</td>
    <td>{referer:body}<div class="formClr"></div>{referer:validation}</td>
    <td>{referer:description}</td>
</tr>
<tr class="rsform-block rsform-block-transition hidden">
    <td>{transition:caption}</td>
    <td>{transition:body}<div class="formClr"></div>{transition:validation}</td>
    <td>{transition:description}</td>
</tr>
<tr class="rsform-block rsform-block-canal hidden">
    <td>{canal:caption}</td>
    <td>{canal:body}<div class="formClr"></div>{canal:validation}</td>
    <td>{canal:description}</td>
</tr>
<tr class="rsform-block rsform-block-campaign hidden">
    <td>{campaign:caption}</td>
    <td>{campaign:body}<div class="formClr"></div>{campaign:validation}</td>
    <td>{campaign:description}</td>
</tr>
<tr class="rsform-block rsform-block-content hidden">
    <td>{content:caption}</td>
    <td>{content:body}<div class="formClr"></div>{content:validation}</td>
    <td>{content:description}</td>
</tr>
<tr class="rsform-block rsform-block-keywords hidden">
    <td>{keywords:caption}</td>
    <td>{keywords:body}<div class="formClr"></div>{keywords:validation}</td>
    <td>{keywords:description}</td>
</tr>
<tr class="rsform-block rsform-block-point hidden">
    <td>{point:caption}</td>
    <td>{point:body}<div class="formClr"></div>{point:validation}</td>
    <td>{point:description}</td>
</tr>
<tr class="rsform-block rsform-block-last_referer hidden">
    <td>{last_referer:caption}</td>
    <td>{last_referer:body}<div class="formClr"></div>{last_referer:validation}</td>
    <td>{last_referer:description}</td>
</tr>


////////////////////////////////////////////////


<p>&nbsp;-----------------------------------------------</p>
<p><strong>{referer:caption}:</strong>&nbsp;{referer:value}</p>
<p><strong>{transition:caption}:</strong>&nbsp;{transition:value}</p>
<p><strong>{canal:caption}:</strong>&nbsp;{canal:value}</p>
<p><strong>{campaign:caption}:</strong>&nbsp;{campaign:value}</p>
<p><strong>{content:caption}:</strong>&nbsp;{content:value}</p>
<p><strong>{keywords:caption}:</strong>&nbsp;{keywords:value}</p>
<p><strong>{point:caption}:</strong>&nbsp;{point:value}</p>
<p><strong>{last_referer:caption}:</strong>&nbsp;{last_referer:value}</p>


////////////////////////////////////////////////

Тип трафика: [referer]
Источник (utm_source): [transition]
Канал (utm_medium): [canal]
Кампания (utm_campaign): [campaign]
Контент (utm_content): [content]
Ключевое слово (utm_term): [keywords]
Точка входа: [point]
Реферер: [last_referer]

////////////////////////////////////////////////