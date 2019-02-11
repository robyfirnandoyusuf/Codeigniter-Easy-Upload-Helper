# Codeigniter Easy Upload Helper

example usage :
``` 
$upload   	= Uploads::single_upload($input = 'image', $this->path);
if(!empty($upload['data']['file_name']))
{	
   $param['image']  		= $upload['data']['file_name'];
}
  ```      
