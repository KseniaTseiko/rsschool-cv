
1. Ksenia Tseiko
2. mail: ktseiko751@gmail.com
   tel: +375296453575
3. At the nearest future i would like to be know and practice my knowledge of programming/development. It is really important to me to realize myself in tihs life. I try to do my best to achive my goals. 
4. php and jQuery(a little bit:)),html5,css3,js,some experience with pug and sass
5." .checkout-form-container.sm-p-15
        form.checkout-delivery-container
            h3.checkout-form-heading Delivery
            .delivery
                .delivery_row
                    input#radioButtonPickup(
                        type='radio'
                        name='pickup'
                        value='pickup')
                    label(for='radioButtonPickup') Pickup
                .delivery_row
                    input#radioButtonDelivery(
                        type='radio'
                        name='delivery'
                        value='delivery')
                    label(for='radioButtonDelivery') Delivery
                .pickup-description= 'Free pickup in Minsk'
                .country-selector#delivery_country
                    label(for='checkout-form-country') Choose your country *
                    input#checkout-form-country(type='text')
                    input#country-code(type='hidden')"
           
        $('#radioButtonPickup').on('change', () => {
        $('#radioButtonDelivery').prop('checked', false);
        $('.pickup-description').show();
        $('#delivery_country').hide();
    });

        $('#radioButtonDelivery').on('change', () => {
        $('#radioButtonPickup').prop('checked', false);
        $('#delivery_country').show();
        $('.pickup-description').hide();
    });
6. I have experience with developing sites on CMS Wordpress.
7. I attended courses in front-end denelopment at IT-school Myfreedom
8. I graduated from Gymnasium №30 (there is minor in english). At the university we have classes of Business english.
