# exor4
	<script>

        document.querySelector('.toggle-password').addEventListener('click', function (e) {
            const passwordInput = document.querySelector('.password-container input');
            const type = passwordInput.getAttribute('type') === 'password' ? 'text' : 'password';
            passwordInput.setAttribute('type', type);
            this.textContent = type === 'password' ? '🔒' : '🔓';
        });

        // <!--

	$(document).ready(function() {
		$( "#dn" ).datepicker({ dateFormat: 'dd/mm/yy', maxDate: '-14y' });
	});

	// -->
	</script>   
