---
title: "Airbobbelz Loot Helper"
permalink: /ab-loot-helper/
---

<script src="/ab-loot-helper.js" />

<b style="color: red;">TEST TEST</b>


<script>
function serialize(objects) {
  
}
  
function deserialize(string) {
  var items = [];
  string.split(';').forEach(item => {
    if (item.indexOf(',') > -1) {
      let item = {};
      item.split(',').forEach(itemPart => {
        const [key, value] = itemPart.split(':');
        item[key] = value;
      })
    } else {
      const [item,chance] = item.split(':');
      items.push({
        item: split[0],
        chance: split[1],
      });
    }
  });
}
</script>
