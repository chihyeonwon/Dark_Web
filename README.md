# 딥웹/다크웹에 접근하는 단계별 가이드

이 문서는 딥웹과 다크웹에 접근하는 방법을 단계별로 안내합니다. 제공되는 지식과 접근할 수 있는 정보는 신중히 다루어야 합니다. 딥웹은 실제로 존재하며, 제대로 보호하지 않으면 위험할 수 있으니 각별히 주의하시기 바랍니다.

---

## TOR이란?

### TOR 로고

### 흔한 오해
- **딥웹에서는 추적이 불가능하다.** `FALSE`
- **다크웹은 범죄자들만 사용하는 곳이다.** `FALSE`
- **딥웹을 탐색하면 체포된다.** `FALSE`
- **딥웹은 누군가 숨기고 싶은 정보를 열람할 수 있는 포털이다.** `PARTIALLY TRUE`
- **검열된 자료에 접근할 수 없다.** `FALSE`
- **딥웹은 뚫을 수 없는 영역이다.** `FALSE`

---

## 1단계 - TOR 다운로드

딥웹에 접근하려면 특별한 브라우저가 필요합니다. TOR를 [여기에서 다운로드](https://www.torproject.org/)하세요. 참고로 TOR는 "The Onion Router"의 약자로, 데이터를 여러 계층(layer)으로 암호화한다는 뜻을 담고 있습니다.

### **익명성을 위한 특별 팁**
딥웹이나 다크웹을 탐색할 때는 익명성을 매우 신중히 유지해야 합니다. 특히 다크넷 마켓에 접근할 경우 더욱 그렇습니다.

1. **VPN(가상사설망)**을 먼저 설정하세요.  
   ISP(인터넷 서비스 제공업체)와 정부 기관은 당신의 온라인 활동을 추적하고 기록할 가능성이 있습니다. 좋은 VPN을 사용하면 ISP나 법 집행 기관도 TOR를 사용하는 사실조차 알 수 없습니다.

---

## 2단계 - 컴퓨터 설정

1. **모든 계정에서 로그아웃**하세요.  
   정말로, 모든 계정에서 로그아웃하세요.
2. **JavaScript, Flash, Java를 비활성화**하세요.  
   Tor는 이 활성 콘텐츠들이 유저 데이터에 접근하거나 공유하는 것을 막지 못합니다.
3. **웹캠을 가리세요.**
4. **조용히 하세요.** 마이크로폰이 모든 대화를 기록할 수 있습니다.

> JavaScript, Flash, Java 등은 Tor의 보호 설정을 우회하여 데이터를 공유할 수 있으며, 이로 인해 추적 가능성이 높아질 수 있습니다.

5. **쿠키 자동 삭제**  
   쿠키는 웹사이트가 당신의 온라인 활동을 추적하거나 정체를 알아내기 위해 사용하는 데이터입니다. "Self-Destructing Cookies" 같은 추가 애드온을 설치해 쿠키를 자동으로 삭제하세요.

---

## 3단계 - 하지 말아야 할 것들

1. **TOR 사용 중 다운로드한 파일 열지 말 것.**  
   PDF나 DOC 문서를 열 경우, 해당 문서에 포함된 악성 코드가 네트워크를 통해 당신의 IP를 노출시킬 가능성이 있습니다.
2. **브라우저 창 크기를 변경하지 말 것.**  
   브라우저 창 크기를 변경하면, 사용 중인 컴퓨터 화면 크기 등의 정보를 노출할 가능성이 있습니다.
3. **HTTP 웹사이트를 피하세요.**  
   Tor는 네트워크 내부의 데이터는 암호화하지만, Tor 외부의 데이터는 암호화하지 않습니다.
4. **Google 사용 금지.**  
   Google은 광고 수익을 위해 사용자의 검색 기록과 데이터를 수집합니다. 대신 StartPage나 DuckDuckGo 같은 검색 엔진을 사용하세요.

---

## 4단계 - Hidden Wiki로 접속 및 탐색 시작

Hidden Wiki 링크를 통해 탐색을 시작하세요.  
**주의**: 이 링크를 온라인으로 공유하지 마세요.  
**금지**: 아동 포르노 등 불법 자료를 보지 마세요.

---

## TOR를 안전하게 사용하려면?

1. **Tor 브라우저 사용**  
   Tor 브라우저를 사용하면 익명성을 유지할 수 있는 최적의 환경을 제공합니다.

2. **토렌트 사용 금지**  
   토렌트는 IP를 노출시킬 수 있으며, Tor 네트워크 전체 속도를 저하시킬 수 있습니다.

3. **브라우저 플러그인 설치 금지**  
   Flash, QuickTime, RealPlayer와 같은 플러그인은 익명성을 해칠 수 있습니다. 추가 플러그인 설치도 권장되지 않습니다.

4. **HTTPS 웹사이트 사용**  
   HTTPS Everywhere 확장 프로그램을 통해 HTTPS 연결을 강제하세요. 브라우저 주소창에서 HTTPS가 포함된 URL인지 확인하세요.

5. **다운로드한 문서 온라인에서 열지 않기**  
   PDF 또는 DOC 문서를 Tor 네트워크에서 열 경우, IP 주소가 노출될 수 있습니다. 반드시 네트워크 연결이 끊긴 상태에서 열도록 하세요.

6. **브리지 사용 및 사용자 확대**  
   Tor 브리지 릴레이를 설정하면 추적 위험을 줄일 수 있습니다. 주변 사람들에게도 Tor 사용을 권장하면 더욱 안전한 환경을 만들 수 있습니다.
