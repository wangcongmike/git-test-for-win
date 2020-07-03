## mike-note

      ```php

            //[PublicController.php]
            public function index($id=0){
	            echo 'id: '.$id;
            }
       ```

      ```ini
            ;页面地址
            www.aritcle.com/admin/public/index     :  将会输出默认值-->  id:0
            www.article.com/admin/public/index/5   :  输出 -->  id:5
      ```