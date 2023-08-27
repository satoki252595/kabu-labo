<script>
  import {
    Card,
    CardText,
    CardActions,
    Button,
    MaterialApp,
  } from "svelte-materialify";

  export let overline = "メンバー限定";
  export let headline = "";
  export let discription = "";
  export let buttonName = "次へ";
  // export let updateDate = "2023/12/12"; //notion APIで取得する
  //export let preUpdateDate = "2023/12/12"; //notion APIで取得する
  export let href = "https://www.buffett-code.com/";
</script>

<MaterialApp>
  <div class="d-flex justify-center mt-4 mb-4">
    <Card outlined style="max-width:300px;">
      <div class="pl-4 pr-4 pt-3">
        <span class="text-overline">
          {overline}
          <div style="flex-grow:1" />

          <br />
          <span class="text-h5 mb-2">{headline}</span>
          <br />
        </span>
      </div>
      <CardText>
        {discription}
      </CardText>
      <CardActions>
        <a {href}>
          <Button rounded outlined>{buttonName}</Button>
        </a>
      </CardActions>
    </Card>
  </div>
</MaterialApp>
