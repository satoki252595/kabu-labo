<script>
  import { AppBar, Button, Icon } from "svelte-materialify";
  import {
    mdiHome,
    mdiHelpCircleOutline,
    mdiCalendarMultiselect,
  } from "@mdi/js";
</script>

<AppBar>
  <div>はぴまねの株ラボ</div>
  &nbsp;&nbsp;&nbsp;
  <div class="d-flex justify-space-between">
    <a href="/">
      <Icon path={mdiHome} />
    </a>
    &nbsp;
    <a
      href="https://www.notion.so/kabu-labo2/2c552cab8b4f43fbac2d1a7cd9419ff8?pvs=4"
    >
      <Icon path={mdiCalendarMultiselect} />
    </a>
    &nbsp;
    <a
      href="https://www.notion.so/kabu-labo2/d8757be876b64611a5b0cd00586e315a?pvs=4"
    >
      <Icon path={mdiHelpCircleOutline} />
    </a>
  </div>
  <div style="flex-grow:1" />

  <a
    href="https://kabu-labo2.notion.site/785e86e1ee8749d986258e4ddb2209f2?pvs=4"
  >
    <Button>サービス内容・メンバー登録</Button>
  </a>
</AppBar>

<style>
  a {
    text-decoration: none;
  }
</style>
