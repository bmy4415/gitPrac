word1                  word2 : multiple spaces => 1space<br/>
word1 &nbsp;&nbsp;&nbsp;&nbsp; : `&nbsp;` => 1space(when want to use multiple spaces)



line1<br/>
line2 : `<br/>` => enter



line4 : 1 enter => nothing, multiple enter => 단락 바뀜

# head1
## head2
### head3
#### head4
##### head5 
###### head6

# 순서있는 목록
1. a
2. b
3. c
2. a

## 순서없는 목록
- my
- name
- is

``를 쓰면 안의 내용물은 마크다운 적용 안됨<br/>
\```을 시작과 끝에 감싸면 multiline 주석<br/>
\```javascript  처럼 언어 명시해주면 언어로 코드도 됨 심지어! <br/>

```
<br/>
# head1
```

``` javascript
var a = 3;
```
<br/>

space4칸도 물론 잘됨, tab으로도 잘됨, 코드작성후 전체를 tab하면 될듯

	for(let i=0; i<10; i++) {

	}

- 탭하고 list를 작성한다면? 잘들어감, \+나 \*문자를 쓰고싶으면 \\를 갈겨버리자
	+ 이건 플러스
		* 이건 별

\>(꺽쇠)이용하면 인용구 가능
> 꺽쇠1개
>> 꺽쇠2개
>>> 꺽쇠3개

잘은 모르겠지만 꺽쇠, \```등등을 쓰면 \<br/>은 따로 안해줘도 되는듯 여긴 일반문장이니 \<br/>사용, 그리고 하나의 component 끝났으면 엔터하나 치는게 좋을듯 <br/>
**두껍게** \** <내용> \**하면 두껍게됨 <br/>
\*1개는 이탤릭, 2개는 두껍게, 3개는 두껍게 이탤릭 <br/>
*이탤릭*, ***두꺼운 이탤릭*** <br/>
\~~ <내용> \~~하면 취소선 ~~cancel~~ <br/> 

\[링크 텍스트]\(링크주소) 특히 \]와 \(사이를 붙여서 써야함<br/>
[naver](www.naver.com) <br/>

마지막은 표인데 표야 좀 되라... 역시나 엔터를 뭔가 잘 써야 되는듯 그래서 \<br\>은 왠지 생각보다 또 안쓸거같기도 한듯, 글에서만 쓸듯 <br/>
사이즈는 가장 긴거에 적당히 맞춰서 되는듯 함 <br/>
정렬은 \---왼쪽 오른쪽에다가 \:붙이면됨 <br/>
:--- 은 왼쪽정렬, ---:은 오른쪽 정렬 

col1                    | col2                |               co  l3 
:--- | --- | ---:
va1 | val2 | val3
2val1 | 2vl2a3 | 2vlasdklasklejasklejalsr4j
a | largeeeeeeeeeeeeeeeeeeee | c
