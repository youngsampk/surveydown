---
format: 
  html:
    theme: cosmo
lang: ko
echo: false
warning: false
footer-left: "Made with [surveydown](https://surveydown.org)"
footer-right: '[<i class="bi bi-github"></i> Source Code](https://github.com/surveydown-dev/templates)'
---

::: {.cell}

:::



::: {.sd_page id=welcome}

# 방학 기간 설문조사

제17기 노사관계전문가과정 원우님들께, 

더운 여름 날씨에 잘 지내고 계신지요?

2학기 개강을 앞두고 지난 번에 약속한대로 간단한 **`설문조사`**를 해보려고 합니다. 
1학기 수업과 강좌운영은 어땠는지, 
그리고 2학기 수업 진행을 좀 더 알차고 유익하게 위해서 개선할 점은 무엇인지, 
여러분들의 의견을 들어보고자 합니다. 

3가지 문항의 짧은 설문조사이기 때문에 잠시만 짬을 내주시면 좋겠습니다. 
그러면 설문을 시작하겠습니다!
`Next` 버튼을 눌러 주세요~



::: {.cell}
::: {.cell-output-display}

```{=html}
<div data-next-page="page1" style="margin-top: 1rem; margin-bottom: 0.5rem;">
<button class="btn btn-default action-button sd-enter-button" id="page_id_next" onclick="Shiny.setInputValue(&#39;next_page&#39;, this.parentElement.getAttribute(&#39;data-next-page&#39;));" style="display: block; margin: auto;" type="button">Next</button>
</div>
```

:::
:::



:::

::: {.sd_page id=page1}



::: {.cell}
::: {.cell-output-display}

```{=html}
<div id="container-bestlec" data-question-id="bestlec" class="question-container" style="width: 100%;" oninput="Shiny.setInputValue(&#39;bestlec_interacted&#39;, true, {priority: &#39;event&#39;});" onclick="Shiny.setInputValue(&#39;bestlec_interacted&#39;, true, {priority: &#39;event&#39;});">
<div id="bestlec" class="form-group shiny-input-checkboxgroup shiny-input-container" role="group" aria-labelledby="bestlec-label">
<label class="control-label" id="bestlec-label" for="bestlec"><p>지난 1학기 수업 중에서 가장 유익했던 강의는 무엇이었나요? 아래 강좌에서 3가지를 골라주세요</p>
</label>
<div class="shiny-options-group">
<div class="checkbox">
<label>
<input type="checkbox" name="bestlec" value="lee"/>
<span>한국의 노동환경과 사회적 대화(이종선 교수)</span>
</label>
</div>
<div class="checkbox">
<label>
<input type="checkbox" name="bestlec" value="yoon"/>
<span>주요 국가의 노사관계와 유형별 특징(윤효원 AIR컨설턴트)</span>
</label>
</div>
<div class="checkbox">
<label>
<input type="checkbox" name="bestlec" value="won"/>
<span>한국노동운동사 100년의 기록(이원보 명예이사장)</span>
</label>
</div>
<div class="checkbox">
<label>
<input type="checkbox" name="bestlec" value="dae"/>
<span>한국 경제사 - 1700년대부터 현재까지(정대영 소장)</span>
</label>
</div>
<div class="checkbox">
<label>
<input type="checkbox" name="bestlec" value="park"/>
<span>우리나라 노동법사(박종희 교수)</span>
</label>
</div>
<div class="checkbox">
<label>
<input type="checkbox" name="bestlec" value="nojo"/>
<span>2025 노동정책 현안과 노동의 대응(정문주 원장 / 이정희 실장)</span>
</label>
</div>
<div class="checkbox">
<label>
<input type="checkbox" name="bestlec" value="emp"/>
<span>2025 노동정책 현안과 기업의 대응(장정우 본부장 / 이명로 본부장)</span>
</label>
</div>
<div class="checkbox">
<label>
<input type="checkbox" name="bestlec" value="kyung"/>
<span>우리나라 기업 노사관계의 주요 유형과 특징(정경은 교수)</span>
</label>
</div>
<div class="checkbox">
<label>
<input type="checkbox" name="bestlec" value="jang"/>
<span>노동과 문학, 우리는 왜 월급지상주의를 쓰는가(장강명 작가)</span>
</label>
</div>
</div>
</div>
<span class="hidden-asterisk">*</span>
</div>
```

:::
:::

::: {.cell}
::: {.cell-output-display}

```{=html}
<div data-next-page="page2" style="margin-top: 1rem; margin-bottom: 0.5rem;">
<button class="btn btn-default action-button sd-enter-button" id="page_id_next" onclick="Shiny.setInputValue(&#39;next_page&#39;, this.parentElement.getAttribute(&#39;data-next-page&#39;));" style="display: block; margin: auto;" type="button">Next</button>
</div>
```

:::
:::


:::

::: {.sd_page id=page2}
몇몇 원우님들께서 강의시작 시간을 오후 6시에서 조금 더 빨리 시작했으면 좋겠다는 강한 희망을 얘기해 주셨습니다. 

지금은 원우님들이 개인 시간을 쪼개서 교육과정에 참여해오고 계신데 일과 중 시간으로 변경하기를 원하는 것 같습니다. 

물론 시간 조정을 위해서는 현재의 `115호실` 강의장을 사용할 수 없을 수도 있고, 다른 강의실 배정을 위해 학교측과 협의를 해보아야 합니다. 확인한 바로는 115호실은 **5시부터 사용하는 것은 가능**하지만 더 빠른 시간으로 옮기기는 어려운 상황입니다. 그리고 미리 초빙이 확정된 `강사님`들의 시간조정이 가능한지도 확인해 보아야 합니다. 

하지만 이런 상황을 감안하더라도 최대한 시간을 앞당겨 조정하기를 원하는 원우님들이 있을 수 있습니다. 그래서 강의 시간을 수정하기를 희망하는지, 어떤 시간으로 수정했으면 하는지 의견을 듣고자 합니다. 



::: {.cell}
::: {.cell-output-display}

```{=html}
<div id="container-yesno" data-question-id="yesno" class="question-container" style="width: 100%;" oninput="Shiny.setInputValue(&#39;yesno_interacted&#39;, true, {priority: &#39;event&#39;});" onclick="Shiny.setInputValue(&#39;yesno_interacted&#39;, true, {priority: &#39;event&#39;});">
<div class="form-group shiny-input-container shiny-input-radiogroup shiny-input-container-inline">
<label class="control-label" id="yesno-label" for="yesno"><p>현재 오후 6시에 시작하는 강의시간을 변경하기를 원하십니까?</p>
</label>
<br/>
<div id="yesno" class="radio-group-buttons">
<div aria-labelledby="yesno-label" class="btn-group btn-group-container-sw" data-toggle="buttons" role="group">
<div class="btn-group btn-group-toggle" role="group">
<button class="btn radiobtn btn-default">
<input type="radio" autocomplete="off" name="yesno" value="keep"/>
지금 시간대가 좋습니다
</button>
</div>
<div class="btn-group btn-group-toggle" role="group">
<button class="btn radiobtn btn-default">
<input type="radio" autocomplete="off" name="yesno" value="change"/>
더 빠른 시간으로 변경하기를 원합니다
</button>
</div>
</div>
</div>
<script>
            $(document).on('click', '#yesno .btn', function() {
                Shiny.setInputValue('yesno_interacted', true, {priority: 'event'});
                // Small delay to allow button state to update
                setTimeout(function() {
                    var selectedValue = '';
                    // Look for checked radio input within the container
                    var checkedInput = $('#yesno input[type="radio"]:checked');
                    if (checkedInput.length > 0) {
                        selectedValue = checkedInput.val();
                    }
                    Shiny.setInputValue('yesno', selectedValue, {priority: 'event'});
                }, 50);
            });
        </script>
</div>
<span class="hidden-asterisk">*</span>
</div>
```

:::
:::

::: {.cell}
::: {.cell-output-display}

```{=html}
<div id="container-time" data-question-id="time" class="question-container" style="width: 100%;" oninput="Shiny.setInputValue(&#39;time_interacted&#39;, true, {priority: &#39;event&#39;});" onclick="Shiny.setInputValue(&#39;time_interacted&#39;, true, {priority: &#39;event&#39;});">
<div class="form-group shiny-input-container shiny-input-radiogroup shiny-input-container-inline">
<label class="control-label" id="time-label" for="time"><p>만약 더 빠른 시간으로 변경하기를 원한다면, 몇 시에 시작하기를 희망하십니까? 선택은 2가지로로만 제시합니다</p>
</label>
<br/>
<div id="time" class="radio-group-buttons">
<div aria-labelledby="time-label" class="btn-group btn-group-container-sw" data-toggle="buttons" role="group">
<div class="btn-group btn-group-toggle" role="group">
<button class="btn radiobtn btn-default">
<input type="radio" autocomplete="off" name="time" value="3"/>
오후 3시
</button>
</div>
<div class="btn-group btn-group-toggle" role="group">
<button class="btn radiobtn btn-default">
<input type="radio" autocomplete="off" name="time" value="5"/>
오후 5시
</button>
</div>
</div>
</div>
<script>
            $(document).on('click', '#time .btn', function() {
                Shiny.setInputValue('time_interacted', true, {priority: 'event'});
                // Small delay to allow button state to update
                setTimeout(function() {
                    var selectedValue = '';
                    // Look for checked radio input within the container
                    var checkedInput = $('#time input[type="radio"]:checked');
                    if (checkedInput.length > 0) {
                        selectedValue = checkedInput.val();
                    }
                    Shiny.setInputValue('time', selectedValue, {priority: 'event'});
                }, 50);
            });
        </script>
</div>
<span class="hidden-asterisk">*</span>
</div>
```

:::
:::

::: {.cell}
::: {.cell-output-display}

```{=html}
<div data-next-page="end" style="margin-top: 1rem; margin-bottom: 0.5rem;">
<button class="btn btn-default action-button sd-enter-button" id="page_id_next" onclick="Shiny.setInputValue(&#39;next_page&#39;, this.parentElement.getAttribute(&#39;data-next-page&#39;));" style="display: block; margin: auto;" type="button">Next</button>
</div>
```

:::
:::



:::

::: {.sd_page id=end}
## 마지막 설문



::: {.cell}
::: {.cell-output-display}

```{=html}
<div id="container-message" data-question-id="message" class="question-container" style="width: 100%;" oninput="Shiny.setInputValue(&#39;message_interacted&#39;, true, {priority: &#39;event&#39;});" onclick="Shiny.setInputValue(&#39;message_interacted&#39;, true, {priority: &#39;event&#39;});">
<div class="form-group shiny-input-container">
<label class="control-label" id="message-label" for="message"><p>알찬 2학기 교육 진행을 위해서 해주고 싶은 말씀이 있으면 직접 남겨 주세요</p>
</label>
<textarea id="message" class="shiny-input-textarea form-control" style="height:100px;" rows="6" cols="80"></textarea>
</div>
<span class="hidden-asterisk">*</span>
</div>
```

:::
:::


설문에 응해주셔서 정말 감사드립니다. 

설문조사 결과를 참고해서 2학기 개강 시간의 변동이 있게 되면 미리 공지하도록 하겠습니다. 
**9월 2일** 2학기 개강일에 뵙겠습니다. 
감사합니다. 

![](logo_ku.png){fig-align="center" width="180"}
<center>**고려대 노동대학원-노동문제연구소 제17기 노사관계전문가과정**</center>
<br>



::: {.cell}
::: {.cell-output-display}

```{=html}
<div style="margin-top: 0.5rem; margin-bottom: 0.5rem;">
<button class="btn btn-default action-button sd-enter-button" id="close-survey-button" onclick="Shiny.setInputValue(&#39;show_exit_modal&#39;, true, {priority: &#39;event&#39;});" style="display: block; margin: auto;" type="button">Exit Survey</button>
</div>
<script>
      Shiny.addCustomMessageHandler('closeWindow', function(message) {
        window.close();
        if (!window.closed) {
          alert('Please close this tab manually to exit the survey.');
        }
      });
    </script>
```

:::
:::


:::

