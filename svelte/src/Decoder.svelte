<script>
  import {Router ,Route ,Link} from "svelte-navigator";
</script>
<div class="container">
    <div class="row" style="padding-top: 50px;">
    <div>
    <form >
        <table style="margin-left:auto;margin-right:auto;">
            <tbody>
                <tr>
                  <td>
                     <div>
                        <div>
    
                            <table>
                            <tbody>
                                <tr>
                                    <td><textarea placeholder="User Agent String " class="form-control" style="height: 208px; width: 508px;"></textarea>
                                    </td>
                                    </tr>
                            </tbody>
                            </table>
                        </div>
                        <br>
                        <center><td><button type="button" class="btn btn-primary btn-lg">Parse user agent string</button></td></center>
                    </td>
                </tr>
            </tbody>
        </table>
    </form>
    </div>
    </div>
    <br><br>
    <div class="row" >
        <div class="card">
        <table class="table table-borderless" >
            <thead>
              <tr  >
                <th scope="col"><h2>Specification</h2></th>  
              </tr>
            </thead>
            <tbody>
              <tr class="table-info">
             
                <th scope="row">OPERATING SYSTEM : </th>
                <td colspan="2"></td>
        
              </tr>
              <tr class="table-info">
            
                <th scope="row">OPERATING SYSTEM VERSION : </th>
                <td colspan="2"></td>
               
              </tr>
              <tr class="table-info">
                <th scope="row">OPERATING SYSTEM LOGO : </th>
                <td colspan="2"></td>
              </tr>
              <tr class="table-info">
                <th scope="row">BROWSER NAME : </th>
                <td colspan="2"></td>
              </tr>
              <tr class="table-info">
                <th scope="row">BROWSER VERSION : </th>
                <td colspan="2"></td>
              </tr>
              <tr class="table-info">
                <th scope="row">BROWSER LOGO : </th>
                <td colspan="2"></td>
              </tr>
            </tbody>
          </table>
          </div>
    </div>
    </div>
