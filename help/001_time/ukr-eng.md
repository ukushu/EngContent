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

  table[data-cell="11"] .c11 { background: #FFE066; }
  table[data-cell="12"] .c12 { background: #FFE066; }
  table[data-cell="13"] .c13 { background: #FFE066; }
  
  table[data-cell="21"] .c21 { background: #FFE066; }
  table[data-cell="22"] .c22 { background: #FFE066; }
  table[data-cell="23"] .c23 { background: #FFE066; }
  
  table[data-cell="31"] .c31 { background: #FFE066; }
  table[data-cell="32"] .c32 { background: #FFE066; }
  table[data-cell="33"] .c33 { background: #FFE066; }

</style>


<table class="myTable">
    <tr>
        <th>Запитання</th>
        <th>Ствердження</th>
        <th>Заперечення</th>
    </tr>
    <tr>
        <td class="c11">
          <div class="horizontalBlocks">
            <div class="redText">Will</div>
            <div class="noun">
              I<br>you<br>we<br>they<br>he<br>she
            </div>
            <div>love?</div>
          </div>
        </td>
        <td class="c12">
          <div class="horizontalBlocks">
            <div class="noun">
              I<br>you<br>we<br>they<br>he<br>she
            </div>
            <div class="redText">will</div>
            <div>love</div>
          </div>
        </td>
        <td class="c13">
          <div class="horizontalBlocks">
            <div class="noun">
              I<br>you<br>we<br>they<br>he<br>she
            </div>
            <div class="redText">won't</div>
            <div>love</div>
          </div>
        </td>
        <td class="side-label">Майбутнє</td>
    </tr>
    <tr>
        <td class="c21">
            <span class="redText">Do</span><br>
            <span class="redText">Does</span>
        </td>
        <td class="c22">
            <div class="noun">
               I<br>you<br>we<br>they<br>he<br>she
            </div>
            <span class="redText">loves</span>
        </td>
        <td class="c23">
            <div class="noun">
               I<br>you<br>we<br>they<br>he<br>she
            </div>
            <span class="redText">don't</span><br><span class="redText">doesn't</span>
        </td>
        <td class="side-label">Теперішнє</td>
    </tr>
    <tr>
        <td class="c31">
          <div class="redText">Did</div>
        </td>
        <td class="c32">
            <div class="noun">
               I<br>you<br>we<br>they<br>he<br>she
            </div>
          <div class="redText">loved</div>
        </td>
        <td class="c33">
            <div class="noun">
               I<br>you<br>we<br>they<br>he<br>she
            </div>
          <div class="redText">didn't</div>
        </td>
        <td class="side-label">Минуле</td>
    </tr>
</table>





