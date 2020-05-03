<div class="section">
    <div>
    	<iframe id="splash" width="960" height="480" src="banners/splash.html"></iframe>
        <div style="top: 70px;font-size: 75px;font-weight: bold;">
        	다음에 무슨 일이 일어날까요?
       	</div>
		<div style="font-weight: 500;top: 140px;left: 10px;font-size: 29px;">
			시뮬레이션으로 설명하는 COVID-19 이후의 미래
		</div>
		<div style="font-weight: 100;top: 189px;left: 10px;font-size: 19px;line-height: 21px;">
			<b>
				🕐 30분 플레이/읽기
				&nbsp;&middot;&nbsp;
			</b>
			<a href="https://scholar.google.com/citations?user=_wHMGkUAAAAJ&amp;hl=en">마르셀 살라테</a>
			(전염병학자)
			&
			<a href="https://ncase.me/">니키 케이스</a>
			(그림/코드)
		</div>
	</div>
</div>

"두려워해야 할 것은 오직 두려움 그 자체이다"는 어리석은 조언이었습니다.

물론, 화장지를 사재기하지 말아야 하죠. 하지만 정책 입안자들이 두려움 자체를 두려워하면, "집단 공황"을 막기 위해 실제 위험을 경시할 것입니다. 두려움은 문제가 아닙니다. 어떻게 두려움을 "극복"하는지가 문제죠. 두려움은 지금 위험에 대처하고, 나중에 있을 위험에 대비할 힘을 줍니다.

솔직히, 우리 (마르셀, 전역병학자 + 니키, 그림/코드)는 걱정하고 있습니다. 당신도 그럴 거라고 생각합니다! 우리의 두려움을 말미암아 **상호작용형 시뮬레이션을** 만들게 되었습니다. *당신도* 두려움을 이해하고 이겨내보세요:

* **지난 몇 달** (역학 101, SEIR 모형, R & R<sub>0</sub>)
* **다음 몇 달** (락다운, 동선 추적, 마스크)
* **다음 몇 년** (면역 손실? 백신 없음?)

이 안내서는 (2020년 5월 1일 발행. 각주를 클릭하세요!→[^timestamp]) 희망 *그리고* 두려움을 주기 위한 것입니다. COVID-19를 **정신 및 재정 건강을 위해**, 계획을 세우려면 낙관적인 생각이 필요하고 백업 계획을 세우려면 비관적인 생각이 필요합니다. 글래디스 브론윈 스턴 작가가 말했듯이, *“낙관주의자는 날 수 있다는 희망에 비행기를 발명하고, 비관주의자는 추락할 수 있다는 염려에 낙하산을 발명합니다.”*

[^timestamp]: 이 각주에는 출처, 링크, 보너스 해설을 포함합니다. 이 해설처럼!

    **이 안내서는 2020년 5월 1일 발행되었습니다.** 많은 세부 사항들이 시대에 뒤떨어지겠지만, 우리는 이 안내서가 95%의 미래를 다루고, 역학 101은 영원히 유용할 것이라고 확신합니다.

자, 이제 단단히 준비하시고 난기류를 경험하세요.

<div class="section chapter">
    <div>
		<img src="banners/curve.png" height=480 style="position: absolute;"/>
        <div>지난 몇 달</div>
    </div>
</div>

비행기 조종사는 추락하지 않기 위해 비행 시뮬레이터를 사용합니다.

**전염병학자들은 인류를 돕기 위해 전염병 시뮬레이터를 사용합니다.**

자, 아주 *아주* 간단한 "전염병 시뮬레이터" 입니다! 이 시뮬레이션에서 <icon i></icon> 감염군은 <icon s></icon> 감염 대상군을 <icon i></icon> 감염시킬 수 있습니다:

![](pics/spread.png)

*발생 초기에* COVID-19 바이러스는 *평균적으로* [^serial_interval] 4일마다 <icon i></icon>에서 <icon s></icon>로 전파되었습니다. (많은 변수가 있다는 것을 명심하세요.)

[^serial_interval]: “평균 [연속] 기간은 3.96일입니다 (95% CI 3.53–4.39일)”. [Du Z, Xu X, Wu Y, Wang L, Cowling BJ, Ancel Meyers L](https://wwwnc.cdc.gov/eid/article/26/6/20-0357_article) (고지 사항: 초기 문서는 최종 버전으로 간주하지 않습니다)

만약 인구의 0.001% <icon i></icon>가 "4일마다 2배씩 늘어나고" *아무것도 하지 않는다고* 가정한다면, 어떻게 될까요?

**시뮬레이션을 재생하시려면 "시작"을 클릭하세요! 나중에 다른 설정으로 해보실 수 있습니다:** (기술 참고 사항: [^caveats])

[^caveats]: **모든 시뮬레이션은 교육 목적으로 단순화되었습니다.**

    단순화: 이 시뮬레이션에 "X일마다 1명씩 감염"이라고 입력하면, 매일 1/X씩 감염자 수가 증가합니다. 이 설정은 다른 시뮬레이션에도 적용됩니다. "X일마다 회복"은 감염자 수가 매일 1/X씩 감소합니다.

    정확하게 *동일하지*는 않지만, 충분히 근접하고, 직접 전염성/회복률을 설정하는 것보다 직관적입니다.

<div class="sim">
		<iframe src="sim?stage=epi-1" width="800" height="540"></iframe>
</div>

이것은 **지수적 성장 곡선입니다.** 처음에는 적은 수로 시작해서 기하 급수적으로 증가하죠. "아 그냥 독감인가" 에서 "아 맞다. 독감으로 *부유한 도시에서 사람들이 대량으로 죽어나가지 않는데*".

![](pics/exponential.png)

하지만 이 시뮬레이션은 틀렸습니다. 다행히도 기하 급수적으로 늘어날 수 없습니다. 다른 사람들이 바이러스를 *이미* 가지고 있으면 바이러스가 전달되지 않습니다:

![](pics/susceptibles.png)

<icon i></icon> 많을수록, <icon s></icon>가 <icon i></icon>로 빠르게 변하지만, <icon s></icon> **적을수록, <icon s></icon>가 <icon i></icon>로 *느리게* 변합니다.**

이 사실로 전염병 성장 곡선이 어떻게 바뀔까요? 한번 알아봅시다:

<div class="sim">
		<iframe src="sim?stage=epi-2" width="800" height="540"></iframe>
</div>

이것은 "S-자형" **로지스틱 성장 곡선입니다.** 처음에는 적은 수로 시작해서 기하 급수적으로 증가하다가 증가 속도가 느려집니다.

하지만 이 시뮬레이션 *역시* 틀렸습니다. <icon i></icon> 감염군은 결국 1) 회복하거나, 2) 폐 손상을 "회복"하거나, 또는 3) 사망함으로써 바이러스를 전달하지 않습니다.

단순화하기 위해, 모든 <icon i></icon> 감염군이 <icon r></icon> 회복군이 되었다고 가정해봅시다. (실제라면 일부는 사망한다는 것을 명심하세요.) <icon r></icon> 회복군은 다시 감염될 수 없으며, *잠시만!* 평생 면역된다고 가정해봅시다.

COVID-19는 <icon i></icon> *평균적으로* [^infectiousness] 10일 동안 감염됩니다. 즉, 10일이 지나기전에 일부는 회복되고, 일부는 그 후에 회복됩니다. **인구의 100%<icon i></icon>로 *시작하면* 다음과 같습니다:**

[^infectiousness]: “평균 전달 가능한 기간은 \[...\] 9.5일입니다.” [Hu, Z., Song, C., Xu, C. et al](https://link.springer.com/article/10.1007/s11427-020-1661-4) 예, "중앙값"과 "평균"은 같지 않다는 것을 알고 있습니다. 단순 교육 목적을 위해 같은 의미로 사용했습니다.

<div class="sim">
		<iframe src="sim?stage=epi-3" width="800" height="540"></iframe>
</div>

이것은 지수적 성장 곡선의 반대인 **지수적 감쇠 곡선입니다.**

이제 S-자형 로지스틱 성장 곡선에 회복을 *포함*해서 가정하면 어떻게 될까요?

![](pics/graphs_q.png)

한번 알아봅시다.

<b style='color:#ff4040'>빨간색 곡선</b>은 *현재* 사례이고 <icon i></icon>,    
<b style='color:#999999'>회색 곡선</b>은 *총* 사례입니다 (현재 확진자 + 회복 <icon r></icon>),
0.001%의 감염군으로 시작<icon i></icon>:

<div class="sim">
		<iframe src="sim?stage=epi-4" width="800" height="540"></iframe>
</div>

여기서 *그* 유명한 곡선이 나옵니다! 종형 곡선은 아니고, "로그 정규분포" 곡선도 아닙니다. 이름은 없습니다. 하지만 이 곡선을 수십억번 보셨고 평평해지기를 바라셨을 겁니다.

이것은 **SIR 모형입니다**,[^sir]    
(<icon s></icon>**S**usceptible 감염대상군 <icon i></icon>**I**nfectious 감염군 <icon r></icon>**R**ecovered 회복군)      
역학 개론에서 *두 번째*로 중요한 개념입니다:

[^sir]: SIR 모형의 더 자세한 설명은 [질병 모형 연구소](https://www.idmod.org/docs/hiv/model-sir.html#)와 [위키피디아](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology#The_SIR_model)를 참고하세요.

![](pics/sir.png)

**참고: 실제 시뮬레이션은 이보다 *훨씬* 더 정교합니다!** 그러나 SIR 모형은 자세한 뉘앙스 없이 일반적인 결과를 설명할 수 있습니다.

실제로 한 단계를 추가해보겠습니다. <icon s></icon> 감염대상군이 <icon i></icon> 감염군이 되기 전에, <icon e></icon> 접촉군이 됩니다. 질병에 감염된 후 잠복기가 있어 아직 전달할 수 없는 상태입니다. *감염*되었지만 아직 *감염*시킬수 없는 상태죠.

![](pics/seir.png)

(이 새로운 질병 확산 모형을 **SEIR 모형**라고 합니다.[^seir], "E"는 <icon e></icon> "Exposed 접촉군"을 의미합니다. 여기서 "접촉"은 바이러스에 감염되었거나 감염되지 않았다는 일상적인 의미가 아닙니다. 의학적인 용어로서, "접촉"은 감염대상군으로부터 감염되었다는 의미입니다. 용어가 좀 헷갈리죠.)

[^seir]: SEIR Model 모형의 더 자세한 설명은 [질병 모형 연구소](https://www.idmod.org/docs/hiv/model-seir.html)와 [위키피디아](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology#The_SEIR_model)를 참고하세요.

COVID-19는 <icon e></icon> *평균적으로* [^latent] 3일 동안 감염되었지만 감염시킬 수 없는 잠복기가 있습니다. 시뮬레이션에 추가하면 어떻게 될까요?

[^latent]: “초기 COVID-19 사례에 관한 연구에서 평균 5.2일의 배양 기간으로 가정할 때, 감염 증상이 나타나기 2.3일 전부터 (95% CI, 0.8–3.0 days) 감염을 시킬 수 있는 것으로 추정했습니다.” (변역: 증상이 5일째 나타난다고 가정했을때, 감염은 2일전부터 전달 가능하다 = 3일째 전달 가능하다.) [He, X., Lau, E.H.Y., Wu, P. et al.](https://www.nature.com/articles/s41591-020-0869-5)

<b style='color:#ff4040'>빨간색 <b style='color:#FF9393'>+ 분홍색</b> 곡선은</b> *현재* 사례이고 (<icon i></icon>감염군 + <icon e></icon>접촉군),    
<b style='color:#888'>회색 곡선은</b> *총* 사례입니다. (current + recovered <icon r></icon>):

<div class="sim">
		<iframe src="sim?stage=epi-5" width="800" height="540"></iframe>
</div>

많이 달라지지 않았습니다! 얼마나 오래 <icon e></icon> 접촉군이냐 <icon e></icon>접촉군-대-<icon i></icon>감염군 비율을 바꾸고 *언제* 현재 사례가 최고점인지를 결정합니다... 하지만 최고점의 *높이*와 총 사례 수는 동일합니다.

왜일까요? 역학 개론에서 *첫 번째*로 중요한 개념때문입니다:

![](pics/r.png)

Short for "Reproduction number". It's the *average* number of people an <icon i></icon> infects *before* they recover (or die).

![](pics/r2.png)

**R**은 면역과 개입 방법이 늘어남이 따라 변화합니다.

**R<sub>0</sub>** (R-노드라고 발음)은 *면역 또는 개입 전에 발병한 시점입니다*. R<sub>0</sub>은 바이러스의 자체의 힘을 더 자세히 반영하지만 장소마다 다릅니다. 예를 들어, R<sub>0</sub>은 시골 지역보다 도시 지역에서 더 높습니다.

(대부분의 뉴스 기사 및 일부 연구 논문에서 R과 R<sub>0</sub>를 혼동 합니다! 용어가 좀 헷갈리죠.)

"그" 계절 독감의 R<sub>0</sub>은 약 1.28[^r0_flu]입니다. 그 말은, 독감 시즌이 *시작될 때* <icon i></icon> 감염군이 *평균적으로* 1.28명을 감염시키는 것입니다. (이 숫자가 정수가 아닌 것이 이상하시면, 엄마들이 "평균" 2.4명의 자녀를 가진다는 것을 생각해보세요. 반명의 아이가 있다는 얘기가 아닙니다.)

[^r0_flu]: “계절 독감의 평균 R값은 1.28명입니다. (IQR: 1.19–1.37)” [Biggerstaff, M., Cauchemez, S., Reed, C. et al.](https://bmcinfectdis.biomedcentral.com/articles/10.1186/1471-2334-14-480)
COVID-19의 R<sub>0</sub>은 약 2.2명으로 추정했습니다.[^r0_covid] 하지만 *아직 진행되고 있는* 한 연구는 우한에서 5.7(!)명이라고 추정했습니다.[^r0_wuhan]

[^r0_covid]: “2019-nCoV의 R0 기초감염재생산수가 약 2.2명으로 추정합니다. (90% high density interval: 1.4–3.8)” [Riou J, Althaus CL.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7001239/)

[^r0_wuhan]: “평균 R0가 약 5.7명으로 추청합니다. (95% CI 3.8–8.9)” [Sanche S, Lin YT, Xu C, Romero-Severson E, Hengartner N, Ke R.](https://wwwnc.cdc.gov/eid/article/26/7/20-0282_article)

시뮬레이션은 *시작과 평균적으로* <icon i></icon> 감염군이 4일마다, 10일 동안 감염시킵니다. "10일"을 "4일"로 나누면 2.5가 됩니다. 이것은 *시작과 평균적으로* 각각의 <icon i></icon> 감염군이 다른 2.5명을 감염시킨다는 말입니다. 따라서, R<sub>0</sub> = 2.5. (주의 사항:[^r0_caveats_sim])

[^r0_caveats_sim]: "감염된 기간" 내내 똑같은 점염성이 있다고 가정했습니다. 역시 교육 목적을 위해 단순화했습니다.

**R<sub>0</sub> 계산기를 이용하여 R<sub>0</sub>가 회복 시간과 새로운 감염까지 걸리는 시간에 어떻게 영향을 미치는지 확인하세요:**

<div class="sim">
		<iframe src="sim?stage=epi-6a&format=calc" width="285" height="255"></iframe>
</div>

하지만 명심하세요. <icon s></icon> 감염대상군이 적을수록, <icon s></icon> 감염대상군이 <icon i></icon>로 *느리게* 감염됩니다. *현재* 감염재생산수 (R)는 *기초* 감염재생산수 (R<sub>0</sub>) 뿐만 아니라, *또한* 얼마나 사람들이 <icon s></icon> 감염대상군에 속하지 않는지도 포함합니다. (예를 들어, 자연면역으로 회복하게 되는 경우를 말합니다.)

<div class="sim">
		<iframe src="sim?stage=epi-6b&format=calc" width="285" height="390"></iframe>
</div>

집단의 대부분이 면역력을 가졌으면, R < 1이며 방역이 이뤄집니다! 이것이 바로 **집단면역*이라고 합니다*. 독감의 경우 *백신으로* 집단면역이 이뤄집니다. 사람들이 감염되도록 방임하여 "자연적으로 집단면역"을 이룬다는 전략은 *끔찍한* 생각입니다. (그러나 생각하시는 이유 때문은 아닐겁니다! 나중에 설명하겠습니다.)

이제 SEIR 모형을 R<sub>0</sub>를 포함해 다시 해봅시다, 시간에 따른 R과 집단면역 임계값을 확인해보세요:

<div class="sim">
		<iframe src="sim?stage=epi-7" width="800" height="540"></iframe>
</div>

**참고: 집단면역의 경우 총 사럐는 *멈추지 않고* 계속 증가합니다!** 그리고 현재 사례가 정점에 도달할때 *정확하게* 집단면역의 사례는 교차합니다. (설정값에 관계없이 발생합니다. 직접 시도해보세요!)

<icon s></icon> 감염대상군이 아닌 사람이 집단면역 임계값보다 더 많을 경우, R < 1 이 되기 때문입니다. 그리고 R < 1 일때, 정점에 이르고 새로운 사례가 없습니다.

**이 안내서에서 한 가지만 얻으신다면, 여기 있습니다.** 굉장히 복잡한 도표이므로 충분한 시간을 두고 숙지하세요:

![](pics/r3.png)

**즉, COVID-19를 멈추기 위해서 모든 감염이나 거의 근접한 감염을 막을 필요 없습니다!**

역설적이죠. COVID-19는 전염성이 매우 높지만, 이겨내기 위해서는 "단지" 60% 이상의 감염만 막으면 됩니다. 60%?! 만약 그게 학교 성적이었다면, D-겠네요. 그러나 R<sub>0</sub> = 2.5인 경우, 61%로 줄이면 R = 0.975, R < 1이 됩니다. COVID-19를 이겨낸 것이죠! (공식:[^exact_formula])

[^exact_formula]:  R = R<sub>0</sub> * 감염병 전파율. 다시말해, 감염병 전파율 = 1 - 감염병 *감소율*.

    R < 1은 R<sub>0</sub> * 감염병 전파율 < 1 가 되어야 합니다.

    감염병 전파율 < 1/R<sub>0</sub> 이며,

    1 - 감염병 감소율 < 1/R<sub>0</sub> 이며,

    감염병 감소율 > 1 - 1/R<sub>0</sub> 이며,

    따라서, 바이러스를 막고 R < 1 되기 위해서는 **1 - 1/R<sub>0</sub>** 이상의 확산을 멈춰야 합니다!

![](pics/r4.png)

(시뮬레이션의 R<sub>0</sub>나 다른 수치가 낮거나/높다고 생각하신다면, 새로운 가정을 세워보세요! 이 안내서 끝에 "샌드박스 모드"가 있습니다. *당신이* 생각하시는 숫자와 그로인한 상황을 시뮬레이션해보세요.)

*모든* COVID-19 예방조치나 추가적인 조치는 - 손 씻기, 사회적/물리적 거리두기, 락다운, 자가 격리, 동선 추적, 쿼런틴, 마스크, "집단면역"도 포함 - *전부* 한 가지 목적을 이루기 위함입니다:

R < 1 되는 것을 목표로 합니다.

자, 이제 우리의 "전염병 시뮬레이터"를 통해 알아봅시다: 어떻게 하면 **정신건강 *그리고* 재정건강을 지키면서** R < 1을 이룰 수 있을까요?

비상착륙을 위해 마음의 준비하세요...

<div class="section chapter">
    <div>
		<img src="banners/curve.png" height=480 style="position: absolute;"/>
        <div>다음 몇 달</div>
    </div>
</div>

...더 끔찍했을 수도 있었습니다. 우리가 피한 평행 우주는 이렇습니다:

###시나리오 0: 아무것도 하지 않았을 경우

COVID-19에 감염된 약 20명 중 1명이 중환자실 (ICU)에 입원합니다. [^icu_covid] 미국과 같은 부유한 나라에서는 3400명당 1 개의 중환자실 병상이 있습니다.[^icu_us] 그러므로, 미국은 *동시에* 3400명당 20명, 즉 인구의 0.6%를 수용할 수 있습니다.

[^icu_covid]: ["2020년 2월 12일부터 3월 16일까지 중환자실 입원이 필요한 미국 COVID-19 연령별 사례 비율"](https://www.statista.com/statistics/1105420/covid-icu-admission-rates-us-by-age-group/). *모든* COVID-19 사례 중 4.9% ~ 11.5%가 중환자실 입원이 필요했습니다. 낮은 연령대의 경우, 5% 였고 20명당 1명이었습니다. 이 총 사례는 미국의 연령 구조에 따른 것이며, 높은 연령대의 인구가 많은 나라에서는 높을 것이고 낮은 연령대의 인구가 많은 나라에서는 낮을 것입니다.

[^icu_us]: “중환자실 병상 수 = 96,596”. [중환자의학회](https://sccm.org/Blog/March-2020/United-States-Resource-Availability-for-COVID-19) 2009년 미국 인구는 약 328,200,000명이었습니다. 328,200,000명당 96,596개의 병실 = 약 3400명당 1개의 병실입니다.

*3배 이상* 늘어나서 2%까지 수용해도, *아무것도 하지 않았을 경우*는 이렇습니다.:*

<div class="sim">
		<iframe src="sim?stage=int-1&format=lines" width="800" height="540"></iframe>
</div>

좋지 않습니다.

 [3월 16일 임페리얼 칼리지 보고서](http://www.imperial.ac.uk/mrc-global-infectious-disease-analysis/covid-19/report-9-impact-of-npis-on-covid-19/)에 따르면: 아무것도 하지 않았을 경우, 중환자실 병실이 현저히 부족하고 인구의 80%가 감염될 것으로 예측했습니다.
(참고: 총 사례가 집단면역을 했을 때 *계속 증가했습니다*)

감염군 0.5%만 사망한다고 해도 - 중환자실이 없을때 가정한 수치 - 미국처럼 큰 나라는 감염된 80%의 0.5%가 사망하면 120만명이나 되는 인구가 사망한 것입니다... *아무것도 하지않았을 때는요.*

(많은 뉴스와 소셜 미디어는 "우리가 아무것도 하지 않았다는* 전제를 *제외하고* "80%가 감염될 것"이라고 보도했습니다. 두려움은 이해가 아닌 클릭으로 이어졌습니다. *아이고.*)

###시나리오 1: 역학 곡선을 평평하게 / 집단면역

모든 공중 보건 기구가 "역학 곡선을 평평하게" 한다는 계획을 내세웠고, 영국의 "집단면역" 전략은 전세계적으로 야유받았습니다. 하지만 *같은 계획입니다.* 영국은 잘못 선전한 것이었죠.[^yong]

[^yong]: “실제 목표는 다른 국가의 목표와 같다고 말했습니다: 감염의 악순환을 저지해서 역학 곡선을 평평하게 만드는 것입니다. 그로인해 집단면역을 달성할 수 있게 됩니다. 집단면역은 목표가 아니라 부가적으로 이뤄지는 것이며 [...] 온라인으로 제공된 정부의 코로나 바이러스 행동 계획서에는 집단면역이 언급되지 않았습니다.”

    [더 아틀란틱 기사, 에드 용 기자](https://www.theatlantic.com/health/archive/2020/03/coronavirus-pandemic-herd-immunity-uk-boris-johnson/608065/)

그러나 두 계획 모두 치명적인 결함이 있었습니다.

먼저, "곡선을 평평하게"하는 두 가지 주요 방법을 살펴 봅시다: 손 씻기 & 물리적 거리두기.

고소득 국가에서 손 씻는 비율이 증가했을때 일반 감기와 독감 발생률이 25%가 감소한 반면에[^handwashing], 대도시 락다운이 내려진 런던의 경우 ~70%까지 감소하였습니다[^london]. 따라서, 손 씻기가 R의 수치를 25%*까지* 감소시키고 거리두기가 R의 수치를 70%*까지* 감소시켰다고 가정해봅시다:

[^handwashing]: “모든 8개의 연구에 따르면, 손 씻기로 호흡기 감염의 위험이 6% 에서 44%까지 감소한 것으로 나타났습니다 [합동분산 24% (95% CI 6–40%)].” 이 시뮬레이션에서는 단순화를 위해 합동분산편차를 25%로 반올림하였습니다. [Rabie, T. and Curtis, V.](https://onlinelibrary.wiley.com/doi/full/10.1111/j.1365-3156.2006.01568.x) 참고: 이 메타 분석에서 집었듯이, 손 씻기에 대한 연구는 (적어도 고소득 국가에서) 제대로 이뤄지지 않았습니다.

[^london]: “피실험자의 평균 일일 접촉 대상의 수는 73% 감소한 것으로 나타났습니다. 이는 R0이 락다운 전 2.6에서 락다운 후 0.62 (0.37 - 0.89)까지 떨어지기에 충분했습니다”. 이 시뮬레이션에서는 단순화를 위해 70% 감소로 반올림하였습니다. [Jarvis and Zandvoort et al](https://cmmid.github.io/topics/covid19/comix-impact-of-physical-distance-measures-on-transmission-in-the-UK.html)

**이 계산기를 사용하여 몇 %의 <icon s></icon> 감염대상군이 아닌 사람들이 손 씻기와 거리두기를 했을때 R을 감소시키는지 확인하세요:** (이 계산기는 *상대적* 효과를 시각화한 것으로, 하나의 효과가 다른 효과를 감소시키는 것처럼 *보입니다.*[^log_caveat])

[^log_caveat]: R을 로그 배율로 적용하면 이 왜곡현상이 없어질 것입니다... 그러면 *로그 배율* 설명해야합니다.

<div class="sim">
		<iframe src="sim?stage=int-2a&format=calc" width="285" height="260"></iframe>
</div>

자, 2020년 3월부터 손 씻는 비율이 증가했다고 가정해보면 어떻게 되는지 시뮬레이션 해봅시다. 3월부터 손 씻는 비율이 증가했고 *가벼운* 물리적 거리두기만 했다고 하면 - R은 감소하지만 여전히 1보다는 높습니다:

<div class="sim">
		<iframe src="sim?stage=int-2&format=lines" width="800" height="540"></iframe>
</div>

세가지 결론:

1. 총 사례가 *감소합니다*! **R < 1는 않았지만, R이 감소하면 여전히 생명을 구할 수 있고, 집단면역의 '계속 증가하는' 현상을 줄입니다.** 많은 사람들은 "역학 곡선을 평평하게"하면 총 사례를 줄이지 않고 퍼뜨린다고 생각합니다. 이것은 *어떠한* 전염병개론에 나오는 모형에서는 불가능 합니다. 그러나 뉴스가 "80% 이상의 사람이 감염될" 것으로 보고했기 때문에 사람들은 총 사례가 무엇이든 상관없이 동일하다고 믿는 것입니다. *에휴.*

2. 추가적인 조치로 인해, 현재 사례는 집단면역이 이뤄지기 *전에* 최고점에 도달합니다. 실제로 이 시뮬레이션에서 총 사례는 영국의 집단면역 계획보다 *아주 약간* 증가합니다. 그 시점에서 R < 1, 다른 조치를 하지않아도 COVID-19를 이겨냅니다. 음, 한 가지 문제를 제외하고서요...

3. 여전히 중환자실에 병실이 부족합니다. 몇 달 동안이나. (이 시뮬레이션에서 이미 *3배나* 중환자실을 늘렸다고 가정한 것을 기억하세요.)

3월 16일 임페리얼 칼리지 보고서에 따르면, 영국이 원래 계획을 포기하게 한 또 다른 발견이 있습니다. **완화**(R 감소, R < 1) 시도는 실패할 것이고, 유일한 방법은 **억제** 시도입니다 (R 감소, R < 1).

![](pics/mitigation_vs_suppression.png)

즉, 단순히 곡선을 "평평하게" 만들지 말고, *부셔야* 합니다. 예를 들어...

###시나리오 2: 몇 달에 걸친 락다운

Let's see what happens if we *crush* the curve with a 5-month lockdown, reduce <icon i></icon> to nearly nothing, then finally – *finally* – return to normal life:

<div class="sim">
		<iframe src="sim?stage=int-3&format=lines" width="800" height="540"></iframe>
</div>

Oh.

This is the "second wave" everyone's talking about. As soon as we remove the lockdown, we get R > 1 again. So, a single leftover <icon i></icon> (or imported <icon i></icon>) can cause a spike in cases that's almost as bad as if we'd done Scenario 0: Absolutely Nothing.

**A lockdown isn't a cure, it's just a restart.**

So, what, do we just lockdown again & again?

###Scenario 3: Intermittent Lockdown

This solution was first suggested by the March 16 Imperial College report, and later again by a Harvard paper.[^lockdown_harvard]

[^lockdown_harvard]: “Absent other interventions, a key metric for the success of social distancing is whether critical care capacities are exceeded. To avoid this, prolonged or intermittent social distancing may be necessary into 2022.” [Kissler and Tedijanto et al](https://science.sciencemag.org/content/early/2020/04/14/science.abb5793)

**Here's a simulation:** (After playing the "recorded scenario", you can try simulating your *own* lockdown schedule, by changing the sliders *while* the simulation is running! Remember you can pause & continue the sim, and change the simulation speed)

<div class="sim">
		<iframe src="sim?stage=int-4&format=lines" width="800" height="540"></iframe>
</div>

This *would* keep cases below ICU capacity! And it's *much* better than an 18-month lockdown until a vaccine is available. We just need to... shut down for a few months, open up for a few months, and repeat until a vaccine is available. (And if there's no vaccine, repeat until herd immunity is reached... in 2022.)

Look, it's nice to draw a line saying "ICU capacity", but there's lots of important things we *can't* simulate here. Like:

**Mental Health:** Loneliness is one of the biggest risk factors for depression, anxiety, and suicide. And it's as associated with an early death as smoking 15 cigarettes a day.[^loneliness]

[^loneliness]: See [Figure 6 from Holt-Lunstad & Smith 2010](https://journals.sagepub.com/doi/abs/10.1177/1745691614568352). Of course, big disclaimer that they found a *correlation*. But unless you want to try randomly assigning people to be lonely for life, observational evidence is all you're gonna get.

**Financial Health:** "What about the economy" sounds like you care more about dollars than lives, but "the economy" isn't just stocks: it's people's ability to provide food & shelter for their loved ones, to invest in their kids' futures, and enjoy arts, foods, videogames – the stuff makes life worth living. And besides, poverty *itself* has horrible impacts on mental and physical health.

Not saying we *shouldn't* lock down again! We'll look at "circuit breaker" lockdowns later. Still, it's not ideal.

But wait... haven't Taiwan and South Korea *already* contained COVID-19? For 4 whole months, *without* long-term lockdowns?

How?

###Scenario 4: Test, Trace, Isolate

*"Sure, we \*could've\* done what Taiwan & South Korea did at the start, but it's too late now. We missed the start."*

But that's exactly it! “A lockdown isn't a cure, it's just a restart”... **and a fresh start is what we need.**

To understand how Taiwan & South Korea contained COVID-19, we need to understand the exact timeline of a typical COVID-19 infection[^timeline]:

[^timeline]: **3 days on average to infectiousness:** “Assuming an incubation period distribution of mean 5.2 days from a separate study of early COVID-19 cases, we inferred that infectiousness started from 2.3 days (95% CI, 0.8–3.0 days) before symptom onset” (translation: Assuming symptoms start at 5 days, infectiousness starts 2 days before = Infectiousness starts at 3 days) [He, X., Lau, E.H.Y., Wu, P. et al.](https://www.nature.com/articles/s41591-020-0869-5)  

    **4 days on average to infecting someone else:** “The mean [serial] interval was 3.96 days (95% CI 3.53–4.39 days)” [Du Z, Xu X, Wu Y, Wang L, Cowling BJ, Ancel Meyers L](https://wwwnc.cdc.gov/eid/article/26/6/20-0357_article)

    **5 days on average to feeling symptoms:** “The median incubation period was estimated to be 5.1 days (95% CI, 4.5 to 5.8 days)” [Lauer SA, Grantz KH, Bi Q, et al](https://annals.org/AIM/FULLARTICLE/2762808/INCUBATION-PERIOD-CORONAVIRUS-DISEASE-2019-COVID-19-FROM-PUBLICLY-REPORTED)

![](pics/timeline1.png)

If cases only self-isolate when they know they're sick (that is, they feel symptoms), the virus can still spread:

![](pics/timeline2.png)

And in fact, 44% of all transmissions are like this: *pre*-symptomatic! [^pre_symp]

[^pre_symp]: “We estimated that 44% (95% confidence interval, 25–69%) of secondary cases were infected during the index cases’ presymptomatic stage” [He, X., Lau, E.H.Y., Wu, P. et al](https://www.nature.com/articles/s41591-020-0869-5)

But, if we find *and quarantine* a symptomatic case's recent close contacts... we stop the spread, by staying one step ahead!

![](pics/timeline3.png)

This is called **contact tracing**. It's an old idea, was used at an unprecedented scale to contain Ebola[^ebola], and now it's core part of how Taiwan & South Korea are containing COVID-19!

[^ebola]: “Contact tracing was a critical intervention in Liberia and represented one of the largest contact tracing efforts during an epidemic in history.” [Swanson KC, Altare C, Wesseh CS, et al.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6152989/)

(It also lets us use our limited tests more efficiently, to find pre-symptomatic <icon i></icon>s without needing to test almost everyone.)

Traditionally, contacts are found with in-person interviews, but those *alone* are too slow for COVID-19's ~48 hour window. That's why contact tracers need help, and be supported by – *NOT* replaced by – contact tracing apps.

(This idea didn't come from "techies": using an app to fight COVID-19 was first proposed by [a team of Oxford epidemiologists](https://science.sciencemag.org/content/early/2020/04/09/science.abb6936).)

Wait, apps that trace who you've been in contact with?... Does that mean giving up privacy, giving in to Big Brother?

Heck no! **[DP-3T](https://github.com/DP-3T/documents#decentralized-privacy-preserving-proximity-tracing)**, a team of epidemiologists & cryptographers (including one of us, Marcel Salathé) is *already* making a contact tracing app – with code available to the public – that reveals **no info about your identity, location, who your contacts are, or even *how many contacts* you've had.**

Here's how it works:

![](pics/dp3t.png)

(& [here's the full comic](https://ncase.me/contact-tracing/))

Along with similar teams like TCN Protocol[^tcn] and MIT PACT[^pact], they've inspired Apple & Google to bake privacy-first contact tracing directly into Android/iOS.[^gapple] (Don't trust Google/Apple? Good! The beauty of this system is it doesn't *need* trust!) Soon, your local public health agency may ask you to download an app. If it's privacy-first with publicly-available code, please do!

[^tcn]: [Temporary Contact Numbers, a decentralized, privacy-first contact tracing protocol](https://github.com/TCNCoalition/TCN#tcn-protocol)

[^pact]: [PACT: Private Automated Contact Tracing](https://pact.mit.edu/)

[^gapple]: [Apple and Google partner on COVID-19 contact tracing technology ](https://www.apple.com/ca/newsroom/2020/04/apple-and-google-partner-on-covid-19-contact-tracing-technology/). Note they're not making the apps *themselves*, just creating the systems that will *support* those apps.

But what about folks without smartphones? Or infections through doorknobs? Or "true" asymptomatic cases? Contact tracing apps can't catch all transmissions... *and that's okay!* We don't need to catch *all* transmissions, just 60%+ to get R < 1.

(Rant about the confusion about pre-symptomatic vs "true" asymptomatic. "True" asymptomatics are rare:[^rant])

[^rant]: Lots of news reports – and honestly, many research papers – did not distinguish between "cases who showed no symptoms when we tested them" (pre-symptomatic) and "cases who showed no symptoms *ever*" (true asymptomatic). The only way you could tell the difference is by following up with cases later.

    Which is what [this study](https://wwwnc.cdc.gov/eid/article/26/8/20-1274_article) did. (Disclaimer: "Early release articles are not considered as final versions.") In a call center in South Korea that had a COVID-19 outbreak, "only 4 (1.9%) remained asymptomatic within 14 days of quarantine, and none of their household contacts acquired secondary infections."

    So that means "true asymptomatics" are rare, and catching the disease from a true asymptomatic may be even rarer!

Isolating *symptomatic* cases would reduce R by up to 40%, and quarantining their *pre/a-symptomatic* contacts would reduce R by up to 50%[^oxford]:

[^oxford]: From the same Oxford study that first recommended apps to fight COVID-19: [Luca Ferretti & Chris Wymant et al](https://science.sciencemag.org/content/early/2020/04/09/science.abb6936/tab-figures-data) See Figure 2. Assuming R<sub>0</sub> = 2.0, they found that:    

    * Symptomatics contribute R = 0.8 (40%)
    * Pre-symptomatics contribute R = 0.9 (45%)
    * Asymptomatics contribute R = 0.1 (5%, though their model has uncertainty and it could be much lower)
    * Environmental stuff like doorknobs contribute R = 0.2 (10%)

    And add up the pre- & a-symptomatic contacts (45% + 5%) and you get 50% of R!

<div class="sim">
		<iframe src="sim?stage=int-4a&format=calc" width="285" height="340"></iframe>
</div>

Thus, even without 100% contact quarantining, we can get R < 1 *without a lockdown!* Much better for our mental & financial health. (As for the cost to folks who have to self-isolate/quarantine, *governments should support them* – pay for the tests, job protection, subsidized paid leave, etc. Still way cheaper than intermittent lockdown.)

We then keep R < 1 until we have a vaccine, which turns susceptible <icon s></icon>s into immune <icon r></icon>s. Herd immunity, the *right* way:

<div class="sim">
		<iframe src="sim?stage=int-4b&format=calc" width="285" height="230"></iframe>
</div>

(Note: this calculator pretends the vaccines are 100% effective. Just remember that in reality, you'd have to compensate by vaccinating *more* than "herd immunity", to *actually* get herd immunity)

Okay, enough talk. Here's a simulation of:

1. A few-month lockdown, until we can...
2. Switch to "Test, Trace, Isolate" until we can...
3. Vaccinate enough people, which means...
4. We win.

<div class="sim">
		<iframe src="sim?stage=int-5&format=lines" width="800" height="540"></iframe>
</div>

So that's it! That's how we make an emergency landing on this plane.

That's how we beat COVID-19.

...

But what if things *still* go wrong? Things have gone horribly wrong already. That's fear, and that's good! Fear gives us energy to create *backup plans*.

The pessimist invents the parachute.

###Scenario 4+: Masks For All, Summer, Circuit Breakers

What if R<sub>0</sub> is way higher than we thought, and the above interventions, even with mild distancing, *still* aren't enough to get R < 1?

Remember, even if we can't get R < 1, reducing R still reduces the "overshoot" in total cases, thus saving lives. But still, R < 1 is the ideal, so here's a few other ways to reduce R:

**Masks For All:**

*"Wait,"* you might ask, *"I thought face masks don't stop you from getting sick?"*

You're right. Masks don't stop you from getting sick[^incoming]... they stop you from getting *others* sick.

[^incoming]: “None of these surgical masks exhibited adequate filter performance and facial fit characteristics to be considered respiratory protection devices.” [Tara Oberg & Lisa M. Brosseau](https://www.sciencedirect.com/science/article/pii/S0196655307007742)

[^outgoing]: “The overall 3.4 fold reduction [70% reduction] in aerosol copy numbers we observed combined with a nearly complete elimination of large droplet spray demonstrated by Johnson et al. suggests that surgical masks worn by infected persons could have a clinically significant impact on transmission.” [Milton DK, Fabian MP, Cowling BJ, Grantham ML, McDevitt JJ](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3591312/)

[^homemade]: [Davies, A., Thompson, K., Giri, K., Kafatos, G., Walker, J., & Bennett, A](https://www.cambridge.org/core/journals/disaster-medicine-and-public-health-preparedness/article/testing-the-efficacy-of-homemade-masks-would-they-protect-in-an-influenza-pandemic/0921A05A69A9419C862FA2F35F819D55) See Table 1: a 100% cotton T-shirt has around 2/3 the filtration efficiency as a surgical mask, for the two bacterial aerosols they tested.

![](pics/masks.png)

To put a number on it: surgical masks *on the sick person* reduce cold & flu viruses in aerosols by 70%.[^outgoing] Reducing transmissions by 70% would be as large an impact as a lockdown!

However, we don't know for sure the impact of masks on COVID-19 *specifically*. In science, one should only publish a finding if you're 95% sure of it. (...should.[^replication]) Masks, as of May 1st 2020, are less than "95% sure".

[^replication]: Any actual scientist who read that last sentence is probably laugh-crying right now. See: [p-hacking](https://en.wikipedia.org/wiki/Data_dredging), [the replication crisis](https://en.wikipedia.org/wiki/Replication_crisis))

However, pandemics are like poker. **Make bets only when you're 95% sure, and you'll lose everything at stake.** As a recent article on masks in the British Medical Journal notes,[^precautionary] we *have* to make cost/benefit analyses under uncertainty. Like so:

[^precautionary]: “It is time to apply the precautionary principle” [Trisha Greenhalgh et al \[PDF\]](https://www.bmj.com/content/bmj/369/bmj.m1435.full.pdf)

Cost: If homemade cloth masks, same as the cost of all that soap for handwashing. If surgical masks, more expensive but still pretty cheap.

Benefit: Even if it's a 50–50 chance of surgical masks reducing transmission by 0% or 70%, the average "expected value" is still 35%, same as a half-lockdown! So let's guess-timate that surgical masks reduce R by up to 35%. (Again, you can challenge our assumptions by turning the sliders up/down)

**Here's a calculator of how masks reduce R! You can switch between cloth & surgical:** (assumes cloth masks are 2/3 as effective as surgical masks[^homemade])

<div class="sim">
		<iframe src="sim?stage=int-6a&format=calc" width="285" height="380"></iframe>
</div>

(other arguments for/against masks:[^mask_args])

[^mask_args]: **"We need to save supplies for hospitals."** *Absolutely agreed.* But that's more of an argument for increasing mask production, not rationing. In the meantime, we can make cloth masks.

   **"They're hard to wear correctly."** It's also hard to wash your hands according to the WHO Guidelines – seriously, "Step 3) right palm over left dorsum"?! – but we still recommend handwashing, because imperfect is still better than nothing.

   **"It'll make people more reckless with handwashing & social distancing."** Sure, and safety belts make people ignore stop signs, and flossing makes people eat rocks. But seriously, we'd argue the opposite: masks are a *constant physical reminder* to be careful – and in East Asia, masks are also a symbol of solidarity!



Masks *alone* won't get R < 1. But if handwashing & "Test, Trace, Isolate" only gets us to R = 1.10, having just 2/3 of people wear *cloth* masks would tip that over to R < 1, virus contained!

**Summer:**

Okay, this isn't an "intervention" we can control, but it will help! Some news outlets report that summer won't do anything to COVID-19. They're half right: summer won't get R < 1, but it *will* reduce R.

For COVID-19, every extra 1° Celsius (2.2° Fahrenheit) makes R drop by 1.2%.[^heat] The summer-winter difference in New York City is 15°C (60°F), so summer will make R drop by 18%.

[^heat]: “One-degree Celsius increase in temperature [...] lower[s] R by 0.0225” and “The average R-value of these 100 cities is 1.83”. 0.0225 ÷ 1.83 = ~1.2%. [Wang, Jingyuan and Tang, Ke and Feng, Kai and Lv, Weifeng](https://papers.ssrn.com/sol3/Papers.cfm?abstract_id=3551767)

<div class="sim">
		<iframe src="sim?stage=int-6b&format=calc" width="285" height="220"></iframe>
</div>

Summer alone won't make R < 1, but if we have limited resources, we can scale back some interventions in the summer – so we can scale them *higher* in the winter.

**A "Circuit Breaker" Lockdown:**

And if all that *still* isn't enough to get R < 1... we can do another lockdown.

But we wouldn't have to be 2-months-closed / 1-month-open over & over! Because R is reduced, we'd only need one or two more "circuit breaker" lockdowns before a vaccine is available. (Singapore had to do this recently, "despite" having controlled COVID-19 for 4 months. That's not failure: this *is* what success takes.)

Here's a simulation a "lazy case" scenario:

1. Lockdown, then
2. A moderate amount of hygiene + "Test, Trace, Isolate" + *cloth* "Masks For All", then...
3. One more "circuit breaker" lockdown before a vaccine's found.

<div class="sim">
		<iframe src="sim?stage=int-7&format=lines&height=620" width="800" height="620"></iframe>
</div>

Not to mention all the *other* interventions we could do, to further push R down:

* Travel restrictions/quarantines
* Temperature checks at malls & schools
* Deep-cleaning public spaces
* [Replacing hand-shaking with foot-bumping](https://twitter.com/V_actually/status/1233785527788285953)
* And all else human ingenuity shall bring

. . .

We hope these plans give you hope.

**Even under a pessimistic scenario, it *is* possible to beat COVID-19, while protecting our mental and financial health.** Use the lockdown as a "reset button", keep R < 1 with case isolation + privacy-protecting contract tracing + at *least* cloth masks for all... and life can get back to a normal-ish!

Sure, you may have dried-out hands. But you'll get to invite a date out to a comics bookstore! You'll get to go out with friends to watch the latest Hollywood cash-grab. You'll get to people-watch at a library, taking joy in people going about the simple business of *being alive.*

Even under the worst-case scenario... life perseveres.

So now, let's plan for some *worse* worst-case scenarios. Water landing, get your life jacket, and please follow the lights to the emergency exits:

<div class="section chapter">
    <div>
		<img src="banners/curve.png" height=480 style="position: absolute;"/>
        <div>The Next Few Years</div>
    </div>
</div>

You get COVID-19, and recover. Or you get the COVID-19 vaccine. Either way, you're now immune...

...*for how long?*

* COVID-19 is most closely related to SARS, which gave its survivors 2 years of immunity.[^SARS immunity]
* The coronaviruses that cause "the" common cold give you 8 months of immunity.[^cold immunity]
* There's reports of folks recovering from COVID-19, then testing positive again, but it's unclear if these are false positives.[^unclear]
* One *not-yet-peer-reviewed* study on monkeys showed immunity to the COVID-19 coronavirus for at least 28 days.[^monkeys]

But for COVID-19 *in humans*, as of May 1st 2020, "how long" is the big unknown.

[^SARS immunity]: “SARS-specific antibodies were maintained for an average of 2 years [...] Thus, SARS patients might be susceptible to reinfection ≥3 years after initial exposure.” [Wu LP, Wang NC, Chang YH, et al.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2851497/) "Sadly" we'll never know how long SARS immunity would have really lasted, since we eradicated it so quickly.

[^cold immunity]: “We found no significant difference between the probability of testing positive at least once and the probability of a recurrence for the beta-coronaviruses HKU1 and OC43 at 34 weeks after enrollment/first infection.” [Marta Galanti & Jeffrey Shaman (PDF)](http://www.columbia.edu/~jls106/galanti_shaman_ms_supp.pdf)

[^unclear]: “Once a person fights off a virus, viral particles tend to linger for some time. These cannot cause infections, but they can trigger a positive test.” [from STAT News by Andrew Joseph](https://www.statnews.com/2020/04/20/everything-we-know-about-coronavirus-immunity-and-antibodies-and-plenty-we-still-dont/)

[^monkeys]: From [Bao et al.](https://www.biorxiv.org/content/10.1101/2020.03.13.990226v1.abstract) *Disclaimer: This article is a preprint and has not been certified by peer review (yet).* Also, to emphasize: they only tested re-infection 28 days later.

For these simulations, let's say it's 1 year.
**Here's a simulation starting with 100% <icon r></icon>**, exponentially decaying into susceptible, no-immunity <icon s></icon>s after 1 year, on *average*, with variation:

<div class="sim">
		<iframe src="sim?stage=yrs-1&format=lines&height=600" width="800" height="600"></iframe>
</div>

Return of the exponential decay!

This is the **SEIRS Model**. The final "S" stands for <icon s></icon> Susceptible, again.

![](pics/seirs.png)

Now, let's simulate a COVID-19 outbreak, over 10 years, with no interventions... *if immunity only lasts a year:*

<div class="sim">
		<iframe src="sim?stage=yrs-2&format=lines&height=600" width="800" height="600"></iframe>
</div>

In previous simulations, we only had *one* ICU-overwhelming spike. Now, we have several, *and* <icon i></icon> cases come to a rest *permanently at* ICU capacity. (Which, remember, we *tripled* for these simulations)

R = 1, it's **endemic.**

Thankfully, because summer reduces R, it'll make the situation better:

<div class="sim">
		<iframe src="sim?stage=yrs-3&format=lines&height=640" width="800" height="640"></iframe>
</div>

Oh.

Counterintuitively, summer makes the spikes worse *and* regular! This is because summer reduces new <icon i></icon>s, but that in turn reduces new immune <icon r></icon>s. Which means immunity plummets in the summer, *creating* large regular spikes in the winter.

Thankfully, the solution to this is pretty straightforward – just vaccinate people every fall/winter, like we do with flu shots:

**(After playing the recording, try simulating your own vaccination campaigns! Remember you can pause/continue the sim at any time)**

<div class="sim">
		<iframe src="sim?stage=yrs-4&format=lines" width="800" height="540"></iframe>
</div>

But here's the scarier question:

What if there's no vaccine for *years*? Or *ever?*

**To be clear: this is unlikely.** Most epidemiologists expect a vaccine in 1 to 2 years. Sure, there's never been a vaccine for any of the other coronaviruses before, but that's because SARS was eradicated quickly, and "the" common cold wasn't worth the investment.

Still, infectious disease researchers have expressed worries: What if we can't make enough?[^vax_enough] What if we rush it, and it's not safe?[^vax_safe]

[^vax_enough]: “If a coronavirus vaccine arrives, can the world make enough?” [by Roxanne Khamsi, on Nature](https://www.nature.com/articles/d41586-020-01063-8)

[^vax_safe]: “Don’t rush to deploy COVID-19 vaccines and drugs without sufficient safety guarantees” [by Shibo Jiang, on Nature](https://www.nature.com/articles/d41586-020-00751-9)

Even in the nightmare "no-vaccine" scenario, we still have 3 ways out. From most to least terrible:

1) Do intermittent or loose R < 1 interventions, to reach "natural herd immunity". (Warning: this will result in many deaths & damaged lungs. *And* won't work if immunity doesn't last.)

2) Do the R < 1 interventions forever. Contact tracing & wearing masks just becomes a new norm in the post-COVID-19 world, like how STI tests & wearing condoms became a new norm in the post-HIV world.

3) Do the R < 1 interventions until we develop treatments that make COVID-19 way, way less likely to need critical care. (Which we should be doing *anyway!*) Reducing ICU use by 10x is the same as increasing our ICU capacity by 10x:

**Here's a simulation of *no* lasting immunity, *no* vaccine, and not even any interventions – just slowly increasing capacity to survive the long-term spikes:**

<div class="sim">
		<iframe src="sim?stage=yrs-5&format=lines" width="800" height="540"></iframe>
</div>

Even under the *worst* worst-case scenario... life perseveres.

. . .

Maybe you'd like to challenge our assumptions, and try different R<sub>0</sub>'s or numbers. Or try simulating your *own* combination of intervention plans!

**Here's an (optional) Sandbox Mode, with *everything* available. (scroll to see all controls) Simulate & play around to your heart's content:**

<div class="sim">
		<iframe src="sim?stage=SB&format=sb" width="800" height="540"></iframe>
</div>

This basic "epidemic flight simulator" has taught us so much. It's let us answer questions about the past few months, next few months, and next few years.

So finally, let's return to...

<div class="section chapter">
    <div>
		<img src="banners/curve.png" height=480 style="position: absolute;"/>
        <div>The Now</div>
    </div>
</div>

Plane's sunk. We've scrambled onto the life rafts. It's time to find dry land.[^dry_land]

[^dry_land]: Dry land metaphor [from Marc Lipsitch & Yonatan Grad, on STAT News](https://www.statnews.com/2020/04/01/navigating-covid-19-pandemic/)

Teams of epidemiologists and policymakers ([left](https://www.americanprogress.org/issues/healthcare/news/2020/04/03/482613/national-state-plan-end-coronavirus-crisis/), [right](https://www.aei.org/research-products/report/national-coronavirus-response-a-road-map-to-reopening/ ), and [multi-partisan](https://ethics.harvard.edu/covid-roadmap)) have come to a consensus on how to beat COVID-19, while protecting our lives *and* liberties.

Here's the rough idea, with some (less-consensus) backup plans:

![](pics/plan.png)

So what does this mean for YOU, right now?

**For everyone:** Respect the lockdown so we can get out of Phase I asap. Keep washing those hands. Make your own masks. Download a *privacy-protecting* contact tracing app when those are available next month. Stay healthy, physically & mentally! And write your local policymaker to get off their butt and...

**For policymakers:** Make laws to support folks who have to self-isolate/quarantine. Hire more manual contact tracers, *supported* by privacy-protecting contact tracing apps. Direct more funds into the stuff we should be building, like...

**For builders:** Build tests. Build ventilators. Build personal protective equipment for hospitals. Build tests. Build masks. Build apps. Build antivirals, prophylactics, and other treatments that aren't vaccines. Build vaccines. Build tests. Build tests. Build tests. Build hope.

Don't downplay fear to build up hope. Our fear should *team up* with our hope, like the inventors of airplanes & parachutes. Preparing for horrible futures is how we *create* a hopeful future.

우리가 두려워해야 할 것은 오직 두려움 그 자체라는 생각이다.
