# Código de Trânsito Brasileiro (Lei 9.503)



PRESIDÊNCIA DA REPÚBLICA

(function(){var f5_cspm={f5_p:'OPEDIPNHPICCHNMMJFIPEFPPHKAGBLBHPAIEGDANLLLIFGEBAKEKKJGLHKGKANODBIGBHAFLAAOHKGEEHGFAMBICAAKJDPBGEGJNOFGLJCDPJHBELGPMGLOKBIFBFDEL',setCharAt:function(str,index,chr){if(index>str.length-1)return str;return str.substr(0,index)+chr+str.substr(index+1);},get_byte:function(str,i){var s=(i/16)|0;i=(i&15);s=s*32;return((str.charCodeAt(i+16+s)-65)>4)+65));str=f5_cspm.setCharAt(str,(i+s),String.fromCharCode((b&15)+65));return str;},set_latency:function(str,latency){latency=latency&0xffff;str=f5_cspm.set_byte(str,40,(latency>>8));str=f5_cspm.set_byte(str,41,(latency&0xff));str=f5_cspm.set_byte(str,35,2);return str;},wait_perf_data:function(){try{var wp=window.performance.timing;if(wp.loadEventEnd>0){var res=wp.loadEventEnd-wp.navigationStart;if(res