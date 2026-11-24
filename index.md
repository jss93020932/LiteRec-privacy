LiteRec ("we", "our", or "the extension") is a zero-server screen recorder for Google Chrome. Your recordings, microphone/camera streams, and personal data stay under your control on your device unless you explicitly choose to upload a recording to your own Google Drive.

---

## English

### 1. Local-First Recording & Storage
- **No LiteRec Media Servers:** All screen captures, tab captures, webcam overlays, audio recordings, snapshots, and MP4 conversions are processed 100% locally inside your browser.
- **Local Storage:** Recordings and preferences are stored locally in your browser via `IndexedDB` and `chrome.storage.local`. We never receive, view, or store your video or audio files on our servers.
- **Permissions Usage:** Camera and microphone access are used strictly while previewing audio levels or actively recording at your request.

### 2. Google Drive Integration & Limited Use Disclosure
- **Scope Requested:** If you connect Google Drive, LiteRec requests only the non-sensitive `https://www.googleapis.com/auth/drive.file` scope. This allows LiteRec to create and manage **only** the files and folder (`LiteRec Recordings`) created by LiteRec itself—never your other Drive files.
- **Account Display:** LiteRec reads your Google account email address via the Drive `about` endpoint solely to display which account is currently connected inside the extension UI.
- **User-Initiated Uploads:** Files are uploaded to your Google Drive **only** when you explicitly click the upload button. Sharing permissions (`anyone with the link`) are applied only when you choose that share mode.
- **Google API Services User Data Policy Compliance:** LiteRec's use and transfer to any other app of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the **Limited Use** requirements.

### 3. Pro License Verification (Lemon Squeezy)
- If you purchase and activate **LiteRec Pro**, the extension communicates directly with Lemon Squeezy (`https://api.lemonsqueezy.com`) to activate and periodically validate your license key.
- Data transmitted and cached locally for licensing is limited to: your `license_key`, a browser-generated `instance_name` / `instance_id` (derived from `chrome.runtime.id`), and the `customer_email` / plan metadata returned by Lemon Squeezy.

### 4. No Tracking, Ads, or Data Sale
- LiteRec does **not** use third-party analytics, tracking pixels, advertising SDKs, or telemetry.
- We do **not** sell, rent, or transfer your personal data or Google user data to third parties or data brokers.

### 5. Data Retention & Deletion
- **Recordings:** Delete individual recordings or clear storage anytime in **LiteRec Studio → Library**.
- **Google Drive Access:** Click **Disconnect** in **LiteRec Studio → Settings** to revoke and clear the cached OAuth token, or revoke access in your [Google Account Permissions](https://myaccount.google.com/permissions).
- **Complete Removal:** Uninstalling the LiteRec extension removes all local `IndexedDB` and `chrome.storage.local` data stored by the extension.

### 6. Contact
For privacy questions or support, please contact the developer via the support email or website listed on LiteRec's Chrome Web Store listing.

---

## 한국어 (Korean)

### 1. 로컬 우선 녹화 및 저장
- **자체 미디어 서버 없음:** 화면/탭 녹화, 웹캠 오버레이, 마이크/시스템 오디오, 스냅샷 및 MP4 변환은 모두 사용자의 브라우저 내부에서만 100% 처리됩니다.
- **로컬 저장소 사용:** 녹화 영상과 설정은 브라우저의 `IndexedDB` 및 `chrome.storage.local`에만 저장되며, 개발자의 서버로 영상이나 오디오가 전송되지 않습니다.
- **마이크·카메라 권한:** 사용자가 녹화를 시작하거나 팝업에서 마이크 입력 레벨을 확인할 때만 사용됩니다.

### 2. Google Drive 연동 및 제한적 사용(Limited Use) 고지
- **요청 권한 범위:** 사용자가 Google Drive 연동을 선택할 경우, LiteRec은 비민감 권한인 `https://www.googleapis.com/auth/drive.file` 범위만 요청합니다. 이는 LiteRec이 직접 생성한 폴더(`LiteRec Recordings`)와 업로드한 파일에만 접근하며, 사용자의 다른 Drive 파일에는 접근하지 않습니다.
- **계정 표시:** Drive `about` API를 통해 조회한 이메일 주소는 확장 프로그램 설정 화면에 연결된 계정을 표시하는 용도로만 사용됩니다.
- **명시적 업로드:** 영상은 사용자가 업로드 버튼을 직접 클릭한 경우에만 Google Drive로 전송되며, 공유 권한(`링크가 있는 모든 사용자`) 역시 사용자가 해당 옵션을 선택한 경우에만 적용됩니다.
- **Google API 사용자 데이터 정책 준수:** Google API로부터 수신한 정보의 사용 및 다른 앱으로의 전송은 **제한적 사용(Limited Use)** 요건을 포함한 [Google API 서비스 사용자 데이터 정책](https://developers.google.com/terms/api-services-user-data-policy)을 준수합니다.

### 3. Pro 라이선스 검증 (Lemon Squeezy)
- **LiteRec Pro** 라이선스 키를 입력하면, 활성화 및 주기적 유효성 검증을 위해 Lemon Squeezy API(`https://api.lemonsqueezy.com`)와 직접 통신합니다.
- 이 과정에서 전송 및 로컬 저장되는 정보는 `license_key`, 확장 프로그램 인스턴스 식별자(`instance_name` / `instance_id`), 그리고 Lemon Squeezy가 반환하는 `customer_email` 및 플랜 정보로 제한됩니다.

### 4. 추적, 광고 및 데이터 판매 없음
- LiteRec은 제3자 분석 도구, 광고 SDK, 추적 스크립트 또는 원격 텔레메트리를 포함하지 않습니다.
- 어떠한 사용자 데이터나 Google 사용자 데이터도 제3자에게 판매, 대여 또는 공유하지 않습니다.

### 5. 데이터 보관 및 삭제 방법
- **녹화 영상 삭제:** **LiteRec Studio → 보관함**에서 언제든지 개별 영상을 삭제할 수 있습니다.
- **Google Drive 연결 해제:** **LiteRec Studio → 설정**에서 **연결 해제(Disconnect)**를 클릭하여 토큰을 폐기하거나 [Google 계정 권한 관리](https://myaccount.google.com/permissions)에서 접근 권한을 철회할 수 있습니다.
- **전체 삭제:** Chrome에서 LiteRec 확장 프로그램을 제거하면 브라우저에 저장된 모든 로컬 데이터(`IndexedDB`, `chrome.storage.local`)가 삭제됩니다.

### 6. 문의
개인정보 처리와 관련한 문의는 Chrome 웹 스토어 LiteRec 페이지에 안내된 개발자 이메일 또는 지원 페이지를 통해 연락해 주세요.
