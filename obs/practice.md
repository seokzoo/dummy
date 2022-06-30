[[practice]]
[[practice#H1]]


# H1
_italic_
*italic*
**bold**
__bold__
- list 1
- list 2
	- list 2a (tab)
- list 3 (shift tab)
1. item 1
2. item 2
	1. item 2a
[Google](https://www.google.com) : https:// 붙여야됨 (다른 schema도 지원)

blockquote
> 피할 수 있으면 피할 수 없을 때까지 피해라

inline code (```` `something` ````)
`print('hello world!')`

code block (```` ``` block ``` ````)
```
for i in range(3):
    print('good')
```

- [ ] checklist

col1 | col2
--------|---------
item1 | item2
item3 | item4

취소선 : ~~deleted~~
하이라이트 : ==highlighted==
수직선
***
---
___

LaTeX support
$$\begin{vmatrix}a & b\\
c & d
\end{vmatrix}=ab-bc$$

%% comments : cannot see it in preview %%


Diagram - Mermaid
```mermaid
sequenceDiagram
    Alice->>+John: Hello John, how are you?
    Alice->>+John: John, can you hear me?
    John-->>-Alice: Hi Alice, I can hear you!
    John-->>-Alice: I feel great!
```

```mermaid
graph TD

A[Biology]
B[Chemistry]

A --> B

class A,B,C,D,E,F,G,H,I,J,K,L,M,N,O,P,Q,R,S,T,U,V,W,X,Y,Z internal-link;
```

```mermaid
graph TD
A[D-글루코스]
A--> |헥소카이네이스| B[D-6인산 글루코스]
B-->C[6인산 프럭토스]
C--> |포스포프럭토카이네이스 PFK-1| D{1, 6양인산 프럭토스}
D-->E[다이하이드록시아세톤 DHAP]
D-->F[3인산글리세르알데히드 PGAL]
E-->G[1,3 양인산 글리세르산 1,3-BPG]
F-->G
G-->H[3 인산 글리세르산 3-PGA]
H-->I[2 인산 글리세르산 2-PGA]
I-->J[인산에놀피루브산 PEP]
J--> |피루브산 카이네이스| K[피루브산]


```