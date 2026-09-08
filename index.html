<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MƯỢN GIÀY KAILAS FUGA RACE VMM 2026</title>
    
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts & Font Awesome Icons -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <script>
        // WEB APP URL GOOGLE APPS SCRIPT:
        const GOOGLE_SCRIPT_URL = 'https://script.google.com/macros/s/AKfycbx2d0_1mZVSDT6mGj8jUgPGqZQZxHLbitbl9APNSwzBHOwiSNByHPFIFpe8zjm5IHKQ/exec';

        // Toggle input for "Size Khác"
        function toggleCustomSizeInput(show) {
            const container = document.getElementById('customSizeContainer');
            const customInput = document.getElementById('customSizeInput');
            if (show) {
                container.classList.remove('hidden');
                customInput.focus();
                customInput.required = true;
            } else {
                container.classList.add('hidden');
                customInput.required = false;
                customInput.value = '';
            }
        }

        async function handleFormSubmit(event) {
            event.preventDefault();

            const submitBtn = document.getElementById('submitBtn');
            const btnIcon = document.getElementById('btnIcon');
            const btnText = document.getElementById('btnText');

            // Extract values
            const fullName = document.getElementById('fullName').value.trim();
            const phoneNumber = document.getElementById('phoneNumber').value.trim();
            const email = document.getElementById('email').value.trim();
            const facebook = document.getElementById('facebook').value.trim();
            const instagram = document.getElementById('instagram').value.trim();
            const itra = document.getElementById('itra').value.trim();
            const estimatedTime = document.getElementById('estimatedTime').value.trim();
            const rentalReason = document.getElementById('rentalReason').value.trim();
            
            const selectedModelEl = document.querySelector('input[name="shoeModel"]:checked');
            const shoeModel = selectedModelEl ? selectedModelEl.value : '';

            let shoeSize = '';
            const selectedSizeEl = document.querySelector('input[name="shoeSize"]:checked');
            if (selectedSizeEl) {
                if (selectedSizeEl.value === 'Khác') {
                    const customVal = document.getElementById('customSizeInput').value.trim();
                    shoeSize = customVal ? `Khác (${customVal})` : 'Khác';
                } else {
                    shoeSize = selectedSizeEl.value;
                }
            }

            const selectedDistEl = document.querySelector('input[name="vmmDistance"]:checked');
            const distance = selectedDistEl ? selectedDistEl.value : '';

            const selectedExpEl = document.querySelector('input[name="kailasExperience"]:checked');
            const kailasExperience = selectedExpEl ? selectedExpEl.value : '';

            // Generate Random Reg Code
            const regCode = 'FUGA-' + Math.floor(100000 + Math.random() * 900000);

            // Payload object
            const formData = {
                regCode: '#' + regCode,
                fullName: fullName,
                phoneNumber: phoneNumber,
                email: email,
                facebook: facebook,
                instagram: instagram,
                itra: itra,
                vmmDistance: distance,
                estimatedTime: estimatedTime,
                shoeModel: shoeModel,
                shoeSize: shoeSize,
                kailasExperience: kailasExperience,
                rentalReason: rentalReason,
                submittedAt: new Date().toLocaleString('vi-VN')
            };

            // Trạng thái nút đang gửi dữ liệu
            if (submitBtn) {
                submitBtn.disabled = true;
                btnIcon.className = 'fa-solid fa-spinner fa-spin';
                btnText.innerText = 'Đang gửi đăng ký...';
            }

            try {
                // Gửi dữ liệu về Google Sheet nếu đã dán GOOGLE_SCRIPT_URL
                if (GOOGLE_SCRIPT_URL && GOOGLE_SCRIPT_URL !== 'DÁN_LINK_WEB_APP_URL_CỦA_BẠN_VÀO_ĐÂY' && GOOGLE_SCRIPT_URL.trim() !== '') {
                    await fetch(GOOGLE_SCRIPT_URL, {
                        method: 'POST',
                        mode: 'no-cors',
                        headers: {
                            'Content-Type': 'application/json'
                        },
                        body: JSON.stringify(formData)
                    });
                }
            } catch (error) {
                console.error("Lỗi gửi dữ liệu lên Google Sheet:", error);
            } finally {
                // Khôi phục nút bấm
                if (submitBtn) {
                    submitBtn.disabled = false;
                    btnIcon.className = 'fa-solid fa-paper-plane';
                    btnText.innerText = 'Gửi Đăng Ký Trải Nghiệm';
                }
            }

            // Populate Summary
            document.getElementById('summaryName').innerText = fullName;
            document.getElementById('summaryPhone').innerText = phoneNumber;
            document.getElementById('summaryModel').innerText = shoeModel;
            document.getElementById('summarySize').innerText = shoeSize;
            document.getElementById('summaryDistance').innerText = distance;
            document.getElementById('summaryCode').innerText = '#' + regCode;

            // Hide form, show success screen
            document.getElementById('formContainer').classList.add('hidden');
            const successCard = document.getElementById('successCard');
            successCard.classList.remove('hidden');
            
            // Smooth scroll to top of success card
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        // Reset Form to register again
        function resetRegistrationForm() {
            document.getElementById('kailasRentalForm').reset();
            toggleCustomSizeInput(false);
            
            document.getElementById('successCard').classList.add('hidden');
            document.getElementById('formContainer').classList.remove('hidden');
            
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }
    </script>
</body>
</html>
