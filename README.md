 jQuery('#additional_wooccm4').on('change', 'input[name="FIELD-ID"]', function() {

        if (jQuery(this).prop('checked') && jQuery(this).val() === '#shipping_method_0_local_pickup7') {
            jQuery('#additional_wooccm4_משלוח חינם לבית הספר').show('slow');
        } else {
            jQuery('#additional_wooccm4_משלוח חינם לבית הספר').hide('slow');
        }
	 								
