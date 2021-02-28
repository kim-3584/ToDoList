# ToDoList
To do list iOS App

- TableViewController

- UIAlertController

- App LifeCycle

  - AppDelegate
    - didFinishLaunchingWithOptions : 앱이 처음 로드되는 순간에 발생. 이것 다음에 최초 화면을 다루는 ViewController 속 viewDidLoad()가 호출된다.
    - didDiscardSceneSessions : AppDelegate는 App을 종료.

  - SceneDelegate
    - sceneDidEnterBackground : 홈버튼을 눌렸을 때, 다른 앱으로 이동할 때 어플리케이션이 백그라운드로 이동.(더 이상 화면에 보이지 않을 때)
    - sceneDidDisconnect : Called as the scene is being released by the system. 
    - sceneWillResignActive : 앱을 보고 있던 중 전화가 걸려오는 등 <일시정지> 상황에 대처할 명령이 있을 때 호출되는 함수. User Data 손실을 막기 위한 코드를 작성할 수 있다.

- Persistent Local Data Storage
