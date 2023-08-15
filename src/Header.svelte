<script>
  import {
    AppBar,
    Button,
    Icon,
    Menu,
    ListItem,
    MaterialApp,
  } from "svelte-materialify";
  import {
    mdiMenu,
    mdiHome,
    mdiCurrencyUsd,
    mdiHelpCircleOutline,
    mdiCalendarMultiselect,
  } from "@mdi/js";
</script>

<AppBar>
  <!-- <Menu>
    <div slot="activator">
      <Button fab depressed>
        <Icon path={mdiMenu} />
      </Button>
    </div>
    <ListItem><a href="/">ホーム</a></ListItem>
    <ListItem><a href="/price">サービス別料金表</a></ListItem>
    <ListItem><a href="/qa">お問い合わせ・よくある質問</a></ListItem>
  </Menu> -->

  <div>はぴまねの株研究所</div>
  &nbsp;&nbsp;&nbsp;
  <div class="d-flex justify-space-between">
    <a href="/">
      <Icon path={mdiHome} />
    </a>
    &nbsp;
    <a
      href="https://www.notion.so/kabu-labo2/bc4353498c22495ea3442009325a9db6?pvs=4"
    >
      <Icon path={mdiCalendarMultiselect} />
    </a>
    &nbsp;
    <a href="/Qa">
      <Icon path={mdiHelpCircleOutline} />
    </a>
  </div>
  <div style="flex-grow:1" />

  <a href="https://happy-money-kabu.stores.jp/items/64d8d6a9260216034a6d8d0c">
    <Button>会員登録</Button>
  </a>
</AppBar>

<style>
  a {
    text-decoration: none;
  }
</style>
