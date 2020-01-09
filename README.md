
<header>
<h1>Summonerswar</h1>

<div>Summoners War Calculator</div>
</header>
<section>
<br/>
<h3><a href="https://veev23.github.io/2018-swar/DamageCalc" target="_blank">서머너즈워 데미지 계산기 링크</a></h3>
<details>
  <summary>데미지 계산기 설명 Click</summary>
  <h4>사용법</h4>
  <hr/>
 <p><b>자동세팅</b>을 이용하거나 실제 몹의 기본스텟을 채워줍니다.</p>
<img src="https://veev23.github.io/2018-swar/1.png">
  <p>사진처럼 나머지 스텟을 채워주고 <b>명예</b>와 <b>깃발</b> %를 채워줍니다.</p>
  <p><b>룬 강화 설정</b>은 룬이 강화가 덜 되었지만 12, 15강 등으로 강화하였을 때의 데미지를 구하고 싶을 때 이용합니다. 체크박스에 체크한 부위만 적용됩니다.</p>
  <p>해당 몬스터의 계수를 모른다면, 페이지 아래의 계수보는곳에 가서 확인합니다. 또는 자동세팅을 이용합니다.<br>영어인 자동세팅은 모든 몹의 계수가 있지만, <b>계수의 타입</b>과 <b>스킬작으로 오르는 데미지</b>는 사용자의 설정이 필요합니다.</p>
  <p><b>무슨계수?</b>는 계수가 어느 것에 의해 영향을 받는지 선택합니다.</p>
  <p><b>스킬계수</b>는 스킬의 계수를 입력합니다. 물이프 2스킬과 같이 단순 공격력 비례라면 1번 계수만 입력하면 되고, 물이프 1스킬의 경우는 (speed+210)/div 형식이므로 1번 계수에는 더하는 값인 210을, 2번 계수에는 나누는 값 div를 입력합니다.
  <br>계수를 음수(-)로 입력한다면, 크리티컬이 뜨지 않는 경우로 계산해줍니다.</p>
  <p><b>스킬작</b>은 스킬로 오르는 피해량을 말합니다. 풍조커 3스의 경우 스킬레벨을 다 올리면 30%의 데미지 증가가 있으므로, 30을 입력합니다.</p>
  <p><b>이계룬</b>은 투지룬이나 결의룬 등을 장착하였을 때 개수를 적습니다. 만약 투지룬 3세트를 장착하였다면 3을 입력합니다.</p>
  <p><b>적의 방어력</b>에는 데미지를 입을 대상의 방어력을 입력합니다. 만약 스킬이 풍조커 3스와 같은 방어무시 데미지라면 0 또는 공란으로 둡니다.</p>
  <p><b>방어력 약화</b>에는 데미지를 입을 대상이 방어력 약화 디버프에 걸렸다면 체크해주고, 아니라면 선택하지 말아주세요.</p>
  <p>다 작성하였다면 Enter키나 계산하기를 눌러주세요. </p>
<p>참고 1 : 입력칸에 아무 수도 적지 않으면 0으로 계산됩니다.</p>
<p>참고 2 : 결과값에 마우스를 대면 룬을 바꾸기 전 데미지도 표시됩니다.(룬 강화는 다 같이 적용됩니다.)</p>
<p>참고 3 : 카이로스 등에서의 데미지를 알고 싶은데 길드레벨에 의한 %증가는 입력칸이 없으므로 다른 데에서 +해주시면 됩니다.</p>
  <p>참고 4 : 몬스터 목록은 제가 직접 업데이트 하는 것이므로 최근에 데미지 상향을 받은 몬스터는 swarfarm.com 등에서 정확한 계수를 확인해주세요..</p> 
</details>
 </section>
 <section>
<h3><a href="https://veev23.github.io/2018-swar/defInversion" target="_blank">서머너즈워 방어력 역산기 링크</a></h3>
<details>
  <summary>방어력 역산기 설명 Click</summary>
<p>방어력에 의한 데미지 감소 1000/(1140*3.5+방어력)임을 이용하여 계산합니다.</p>
<p>계산기상의 데미지 : <a href="https://veev23.github.io/2018-swar/DamageCalc" target="_blank">계산기</a>에서 적의 방어력이 "0"일 때 나온 결과값을 입력합니다.</p>
<p><b>적에게 가한 데미지</b> : 실제로 때렸을 때 데미지를 입력합니다.</p>
<p><b>적의 기본 방어력</b> : 때린 적의 기본 방어력을 입력합니다.</p>
<p><b>방어력 감소</b> : 적이 방어력 감소가 걸렸을 때 데미지를 주었다면 선택합니다.</p>
<p><b>길드전</b> : 길드전이면서 적의 길드깃발이 최대치(방어력 20%)라고 가정합니다.</p>
<p><b>명예건물</b> : 적의 명예건물이 최대치(방어력 20%)라고 가정합니다.</p>
<br/>
<p>계산기상의 데미지는 소숫점을 버리고, 실제 데미지는 이론상 데미지에서 오차가 있기 때문에 결과값으로 나오는 방어력은 실제와의 차이가 있습니다.</p>
</details>
  
<h3><a href="https://veev23.github.io/2018-swar/emperor-garuda-raid" target="_blank">뇌가드 테스터 링크</a></h3>
<details>
  <summary>뇌가드 테스터 설명 Click</summary>
  </details>
  </section>
<footer>
  </footer>
