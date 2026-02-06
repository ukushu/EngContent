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
    font-weight: bold;
  }
  .highlight {
    background-color: #FFF3B0;
  }
  
  .noun {
      color: #AAAAAA;
  }

  .horizontalBlocks {
    display: flex; 
    gap: 10px; 
    align-items: center; 
    padding: 10px;
  }

  .verticalBlocks {
    
  }

  table[data-cell="11"] .c11 { background: rgba(0, 140, 0, 0.5); }
  table[data-cell="12"] .c12 { background: rgba(0, 140, 0, 0.5); }
  table[data-cell="13"] .c13 { background: rgba(0, 140, 0, 0.5); }
  
  table[data-cell="21"] .c21 { background: rgba(0, 140, 0, 0.5); }
  table[data-cell="22"] .c22 { background: rgba(0, 140, 0, 0.5); }
  table[data-cell="23"] .c23 { background: rgba(0, 140, 0, 0.5); }
  
  table[data-cell="31"] .c31 { background: rgba(0, 140, 0, 0.5); }
  table[data-cell="32"] .c32 { background: rgba(0, 140, 0, 0.5); }
  table[data-cell="33"] .c33 { background: rgba(0, 140, 0, 0.5); }

</style>


<table class="myTable" data-cell="11">
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
        <th class="side-label">Майбутнє</th>
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
            <span class="redText">love</span><span class="highlight">s</span>
        </td>
        <td class="c23">
            <div class="noun">
               I<br>you<br>we<br>they<br>he<br>she
            </div>
            <span class="redText">don't</span><br><span class="redText">doesn't</span>
        </td>
        <th class="side-label">Теперішнє</th>
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
        <th class="side-label">Минуле</th>
    </tr>
</table>
<br>
  <li>"won't" = "will not"</li>
  <li>"don't" = "do not"</li>
  <li>"doesn't" = "does not"</li>
  <li>"didn't" = "did not"</li>
</ul>




