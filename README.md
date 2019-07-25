# php-
简便轻松的完成阿里云短信发送开发

测试代码：use引入，实例化直接用
use Sms\Sms;

class Test{
    public function index(){
        $sms = new Sms();
        $res = $sms->sendSms('17628004267');
        dump($res);
    }
}
