<style>
  table.myTable {
    border-collapse: collapse;
  }
  table.myTable td {
    border: 1px solid white;
    padding: 5px;
    vertical-align: middle;
  }
  .redText {
    color: #CC0000;
  }
  .noun {
      color: #AAAAAA;
  }

  .horizontalBlocks {
    display: flex; 
    gap: 10px; 
    align-items: center; 
    padding: 15px;
  }

  .verticalBlocks {
    
  }

</style>


<table class="myTable">
    <tr>
        <th>Запитання</th>
        <th>Ствердження</th>
        <th>Заперечення</th>
        <th rowspan="3" class="side-label">Майбутнє</th>
    </tr>
    <tr>
        <td>
          <div class="horizontalBlocks">
            <div class="redText">Will</div>
            <div class="noun">
              I<br>you<br>we<br>they<br>he<br>she
            </div>
            <div>love?</div>
          </div>
        </td>
        <td>
          <div class="horizontalBlocks">
            <div class="noun">
              I<br>you<br>we<br>they<br>he<br>she
            </div>
            <div class="redText">will</div>
            <div>love</div>
          </div>
        </td>
        <td>
          <div class="horizontalBlocks">
            <div class="noun">
              I<br>you<br>we<br>they<br>he<br>she
            </div>
            <div class="redText">won't</div>
            <div>love</div>
          </div>
        </td>
    </tr>
    <tr>
        <td>
            <span class="redText">Do</span><br>
            <span class="redText">Does</span>
        </td>
        <td>
            <div class="noun">
               I<br>you<br>we<br>they<br>he<br>she
            </div>
        </td>
        <td>
            <div class="noun">
               I<br>you<br>we<br>they<br>he<br>she
            </div>
        </td>
    </tr>
    <tr>
        <td></td>
        <td>
            <span class="redText">loves</span>
        </td>
        <td>
            <span class="redText">don't</span><br><span class="redText">doesn't</span>
        </td>
    </tr>
    <tr>
        <td class="redText">Did</td>
        <td>
            <div class="noun">
               I<br>you<br>we<br>they<br>he<br>she
            </div>
        </td>
        <td>
            <div class="noun">
               I<br>you<br>we<br>they<br>he<br>she
            </div>
        </td>
    </tr>
    <tr>
        <td></td>
        <td class="redText">loved</td>
        <td class="redText">didn't</td>
    </tr>
</table>

