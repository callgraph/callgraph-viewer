# callgraph-viewer
Callgraph Viewer  
edited by Cao Ruidong
## dependence
DB and corresponding data table
## callgraph-perl 
script that draws SVG for callgraph  
### Arguments  
ARGV[0] $ver_v：版本  
ARGV[1] $ver_a：平台  
ARGV[2] $ver_f：目录类型  
ARGV[3] $path0：起始路径   
ARGV[4] $path1：目标路径  
ARGV[5] $che1：是否放大  
ARGV[6] $sourceroot：文件存放路径  
ARGV[7] $sh_ruby_source：调用的ruby脚本所在的目录  
ARGV[8] $baseurl：服务器网址  
ARGV[9] $ddir：SVG存放的根路径（无版本和平台）  
ARGV[9] $code_url：代码网址  
ARGV[0] $note_url：注释网址  
## callgraph-sql.rb
script that gets data from DB and making dot
### Arguments   
## pic.rb
script that makes SVG from dot
### Arguments  
## amplify.rb
script that draws amplified SVG
### Arguments  
