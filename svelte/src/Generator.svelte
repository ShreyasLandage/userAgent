<script>
    import { Router, Route, Link } from "svelte-navigator";

</script>
<div style="margin-top: 150px; margin-bottom:150px" class="container ">
    <div class="row">
        <div class="col"></div>
        <div class="col">
        <form class="form-inline">
            <div class="row">
            <div class="col">

              <input type="number" class="form-control shadow" placeholder="Max Limit">
            </div>
            <div class="col">
            <button type="submit" class="btn btn-primary mb-2 shadow">Submit</button>
            </div>
            </div>
          </form>
          </div>
          <div class="col"></div>
      <div class="w-100"></div>
      <br><br><br><br>
      <div class="list-group shadow">
       <h2  style="text-align:center; font-family:'Times New Roman', Times, serif ; background-color : rgb(75, 93, 250);color:white" >Result</h2>
        <a href="#" class="list-group-item list-group-item-action">link 1</a>
        <a href="#" class="list-group-item list-group-item-action">link 2</a>
        <a href="#" class="list-group-item list-group-item-action">link 3</a>
        <a href="#" class="list-group-item list-group-item-action">link 4</a>
      </div>
    </div>
  </div>