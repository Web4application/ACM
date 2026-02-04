##
##
##        Mod title:  Sur.ly
##
##      Mod version:  3.0.0
##  Works on FluxBB:  1.5.10
##     Release date:  2017-03-01
##           Author:  surdotly (surdotly@gmail.com)
##
##      Description:  Sur.ly alters the outbound links on your site so that visitors can view external target pages without leaving your domain.
##
##   Affected files:  admin_loader.php
##                    viewtopic.php
##
##       Affects DB:  Yes
##
##       DISCLAIMER:  Please note that "mods" are not officially supported by
##                    FluxBB. Installation of this modification is done at 
##                    your own risk. Backup your forum database and any and
##                    all applicable files before proceeding.
##
##


#
#---------[ 1. UPLOAD ]-------------------------------------------------------
#

Upload all the files from the folder /files to your FTP.


#
#---------[ 2. RUN ]----------------------------------------------------------
#

install_mod.php


#
#---------[ 3. DELETE ]-------------------------------------------------------
#

install_mod.php


#
#---------[ 4. OPEN ]---------------------------------------------------------
#

admin_loader.php


#
#---------[ 5. FIND ]---------------------------------------------------------
#

require PUN_ROOT.'include/common_admin.php';


#
#---------[ 6. AFTER, ADD ]---------------------------------------------------
#

require PUN_ROOT.'include/surly/common_admin.php';


#
#---------[ 7. OPEN ]---------------------------------------------------------
#

viewtopic.php


#
#---------[ 8. FIND ]---------------------------------------------------------
#

require PUN_ROOT.'include/common.php';


#
#---------[ 9. AFTER, ADD ]---------------------------------------------------
#

require PUN_ROOT.'include/surly/surly.php';


#
#---------[ 10. FIND ]--------------------------------------------------------
#

				if ($pun_config['o_censoring'] == '1')
					$cur_post['url'] = censor_words($cur_post['url']);


#
#---------[ 11. AFTER, ADD ]--------------------------------------------------
#

				$cur_post['url'] = surly_replace_url($cur_post['url'], $cur_post['g_id']);


#
#---------[ 12. FIND ]--------------------------------------------------------
#

	$cur_post['message'] = parse_message($cur_post['message'], $cur_post['hide_smilies']);


#
#---------[ 13. AFTER, ADD ]--------------------------------------------------
#

	$cur_post['message'] = surly_replace($cur_post['message'], $cur_post['g_id']);


#
#---------[ 14. FIND ]--------------------------------------------------------
#

		if (isset($signature_cache[$cur_post['poster_id']]))
			$signature = $signature_cache[$cur_post['poster_id']];
		else
		{
			$signature = parse_signature($cur_post['signature']);
			$signature_cache[$cur_post['poster_id']] = $signature;
		}


#
#---------[ 15. AFTER, ADD ]--------------------------------------------------
#

		$signature =  surly_replace($signature, $cur_post['g_id']);


#
#---------[ 16. SAVE/UPLOAD ]-------------------------------------------------
#