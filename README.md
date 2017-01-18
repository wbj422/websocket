# websocket
手机间的即时通讯代码，后台socket

Applications\YourApp\Config\Db.php 需要配置上你的数据库信息
Applications\YourApp\controller\ConfigController.class.php 需要配置上你的服务器ip
Controller.class.php controller里面的控制器继承这个类，里面有记录消息到数据库，发送即时消息，发送推送等。这些都需要自己去实现，涉及到这部分的代码，已经删掉了，自己可以根据自己的情况建立数据库和接上自己的推送代码。
