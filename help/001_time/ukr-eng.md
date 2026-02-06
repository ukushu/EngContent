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
    color: #C85050;
    font-weight: bold;
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
    display: flex;
    flex-direction: column;
    gap: 20px;
  }

  table[data-cell="11"] .c11 { background: rgba(0, 140, 0, 0.3); }
  table[data-cell="12"] .c12 { background: rgba(0, 140, 0, 0.3); }
  table[data-cell="13"] .c13 { background: rgba(0, 140, 0, 0.3); }
  
  table[data-cell="21"] .c21 { background: rgba(0, 140, 0, 0.3); }
  table[data-cell="22"] .c22 { background: rgba(0, 140, 0, 0.3); }
  table[data-cell="23"] .c23 { background: rgba(0, 140, 0, 0.3); }
  
  table[data-cell="31"] .c31 { background: rgba(0, 140, 0, 0.3); }
  table[data-cell="32"] .c32 { background: rgba(0, 140, 0, 0.3); }
  table[data-cell="33"] .c33 { background: rgba(0, 140, 0, 0.3); }

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
          <div class="verticalBlocks">
            <div class="horizontalBlocks">
              <div class="redText">Do</div>
              <div class="noun">
                 I<br>you<br>we<br>they
              </div>
              <div>
                 love
              </div>
            </div>
            <div class="horizontalBlocks">
              <div class="redText">Does</div>
              <div class="noun">
                 he<br>she
              </div>
              <div>
                 love
              </div>
            </div>
          </div>
        </td>
        <td class="c22">
          <div class="verticalBlocks">
            <div class="horizontalBlocks">
              <div class="noun">I<br>you<br>we<br>they</div>
              <div>love</div>
            </div>
            <div class="horizontalBlocks">
              <div class="noun">he<br>she</div>
              <div>love<span class="redText">s</span></div>
            </div>
          </div>
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
          <div>lov<span class="redText">ed</span></div>
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




