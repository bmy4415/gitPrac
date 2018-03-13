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

space4칸도 물론 잘됨
    
    for(let i=0; i<10; i++) {
    
    }

