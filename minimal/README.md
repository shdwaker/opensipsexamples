# Minimilistic configuration of opensips 

using modules **sipmsgops** which provides functions such as 
filter_body(content_type)
append_to_reply(txt)
append_hf(txt)
append_hf(txt, hdr)
insert_hf(txt)
insert_hf(txt, hdr)
append_urihf(prefix, suffix)
is_present_hf(hf_name)
append_time()
is_method(name)
remove_hf(hname [,flags])
has_body(), has_body(mime)
is_audio_on_hold()
is_privacy(privacy_type)
strip_body(), strip_body(mime)
add_body(body_text, new_content_type)
sipmsg_validate([flags[,result_pvar]])
codec_exists (name [,clock] )
codec_delete (name [,clock] )
codec_move_up (name [,clock] )
codec_move_down (name [,clock] )
codec_exists_re ( regexp )
codec_delete_re ( regexp )
codec_delete_except_re ( regexp )
codec_move_up_re ( regexp )
codec_move_down_re ( regexp )
change_reply_status(code, reason)
stream_exists(regexp)
stream_delete(regexp)
