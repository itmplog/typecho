## Typecho_Widget class

	abstract class Typecho_Widget

* private static $_widgetPool = array();
* private static $_widgetAlias = array();
* private $_helpers = array();
* protected $row = array();
* public $stack = array();
* public $sequence = 0;
* public $length = 0;
* public $request;
* public $response;
* public $parameter;

* public function __construct($request, $response, $params = NULL)
* protected function __parseCallback($matches)
* public function on($condition)
* new Typecho_Widget_Helper_Empty();
* public function pluginHandle($handle = NULL)
* Typecho_Plugin::factory(empty($handle) ? get_class($this) : $handle);
* public static function alias($widgetClass, $aliasClass)
* public static function widget($alias, $params = NULL, $request = NULL, $enableResponse = true)
* throw new Typecho_Widget_Exception($className);
* new Typecho_Request()
*  $responseObject = $enableResponse ? Typecho_Response::getInstance()
            : Typecho_Widget_Helper_Empty::getInstance();
* public static function destory($alias)
* public function to(&$variable)
* public function parse($format)
* public function push(array $value)
* public function alt()
* public function sequence()
* public function have()
* public function next()
* public function __call($name, $args)
* public function __get($name)
* public function __set($name, $value)
* public function __isSet($name)
