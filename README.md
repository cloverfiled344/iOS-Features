# iOS-Features
Road map for Swift programming !
Step First !!!!

Beginner level: 
* iOS, Swift, Xcode, Tools - Понимание экосистемы Apple; понимание языка программирования ; Использование редактора кода Xcode для разработки приложения под iOS систему. 
* Понимание принципов объявления переменных ; Понятие глобальности и локальных сущностей ; 
* Swift - Понимание языка , строгая типизация ЯП(Языка программирования)

Intern level - Я разделил на две части : UI and Swift (technical knowledge) 
Оставлю по мере нужды ссылки на источники или видеоуроки по разработке , чтобы укрепить полученные знания 

Intern level - UI side : https://www.youtube.com/watch?v=Nd8t60o7tIg&list=PLRJuPW6BGThvPVkbTua6i2TKomig76b2K/
(Кандидат должен владеть самыми минимальными знаниями ):  
* UI - (Storyboard <=> Interface Builder) or with сode (UI creating -> UIKit) 
* Умение верстать самый тривиальный дизайн (Одна страница , TableView or CollectionView -> With CellItems: Label, Button, Switcher, UITextField)
* Работа с Коллекциями  (UITableView, UICollectionView) , принцип их работы , сколько ячеек создается на экране , работа с reusable 
* Понимание легких паттернов программирования и применения их на практике (Singletone, NotificationCenter, Delegate)
* Сетевые запросы (URLSession, Alamofire) - достаточно запарсить JSON из request

Xcode hotkeys: https://habr.com/ru/post/307138/

Intern level - technical side
* Struct vs Class - Зачем они в Swift ? Value vs Reference types , Stack and Heap (Зачем они нужны, где и в каких местах мы используем их?)
* Let vs Var - Для чего мы используем эти ключевые слова , в чем отличие ? (Mutable vs Immutable)
* Optionals - Для чего нужны опционалы и какую проблему они способствуют решить ? 
* Protocols - Зачем мы их используем ? 
* Access Modifiers - (private, fileprivate, open, public, internal)
* Collections - (Basic: Array, Set, Dictionary) , (String, Tuple, Range, Sequence) -> Все ли объекты могут быть ключом Dictionary ? (Подсказка -> Hashable, Equatable)
* Как память работает ? (ARC - зачем он нужен в Swift ? MRC - перестали его использовать ?)
* Generics - Как они работают ? Для чего используют ? 

Junior level - UI side
* Frameworks, Libraries - UIKit(required) , (Texture - optional)
* Adaptive UI , AutoLayout - (Умение разбираться в коде , решать конфликты констрейнтов , верстать адаптивный дизайн)
* UI Collections - (TableView, CollectionView, CustomView - умение разбирать структуры данных view,  умение использовать разные форматы коллекций) 
* Dependencies in iOS projects - CocoaPods, SPM, Mint, Carthage and others

Junior level - Technical side 
* Design Patterns - (Creational , Structural, Behavioral) https://refactoring.guru/ru/design-patterns 
* Architecture Patterns - MVVM, MVC, Coordinator, VIP, VIPER, MVVM + Combine, MVVM + RXSwift: https://habr.com/ru/company/badoo/blog/281162/
* Life cycle of UIVIewController : https://habr.com/ru/post/129557
* Life cycle of iOS application : https://proswift.ru/ios-application-lifecycle-ili-zhiznennyj-cikl-ios-prilozheniya
* ARC - (Stack vs Heap) -> weak, unowned, strong references (Зачем нам нужны эти ссыки ? Как работает ARC ? ) 
* Memory Management (SIDETABLE  - what we need ?) - https://habr.com/ru/post/451130 , https://habr.com/ru/company/hh/blog/546856
* 

