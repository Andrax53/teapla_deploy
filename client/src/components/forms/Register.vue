<template xmlns="http://www.w3.org/1999/html">
    <article class="wizard-form">
        <form class="form-register" action="#" method="post">
            <section id="form-total" role="application" class="wizard clearfix vertical content-back">
                <div class="steps clearfix">
                    <ul role="tablist">
                        <li role="tab" aria-disabled="false" class="first current" aria-selected="true"><a
                                id="form-total-t-0" href="#form-total-h-0" aria-controls="form-total-p-0"><span
                                class="current-info audible"> </span>
                            <div class="title">
                                <p class="step-icon"><span>01</span></p>
                                <span class="step-text">Основная информация</span>
                            </div>
                        </a></li>
                        <li role="tab" aria-disabled="false"><a id="form-total-t-1" href="#form-total-h-1"
                                                                aria-controls="form-total-p-1">
                            <div class="title">
                                <p class="step-icon"><span>02</span></p>
                                <span class="step-text">Тематика курса</span>
                            </div>
                        </a></li>
                        <li role="tab" aria-disabled="false" class="last"><a id="form-total-t-2" href="#form-total-h-2"
                                                                             aria-controls="form-total-p-2">
                            <div class="title">
                                <p class="step-icon"><span>03</span></p>
                                <span class="step-text">Уровень сложности</span>
                            </div>
                        </a></li>
                    </ul>
                </div>
                <div class="content clearfix">
                    <h2 id="form-total-h-0" tabindex="-1" class="title current">
                        <p class="step-icon"><span>01</span></p>
                        <span class="step-text">Peronal Infomation</span>
                    </h2>
                    <section id="form-total-p-0" role="tabpanel" aria-labelledby="form-total-h-0" class="body current"
                             aria-hidden="false">
                        <div class="inner">
                            <div class="wizard-header">
                                <h3 class="heading">Основная Информация</h3>
                                <p>Укажите основную информацию вашего курса и приступайте к следующему шагу</p>
                            </div>
                            <div class="form-row">
                                <div class="form-holder">
                                    <fieldset>
                                        <legend>Название</legend>
                                        <input type="text" class="form-control" id="first-name" name="first-name"
                                               placeholder="Название курса" required="">
                                    </fieldset>
                                </div>
                                <div class="form-holder">
                                    <fieldset>
                                        <legend>Тег</legend>
                                        <input type="text" class="form-control" id="last-name" name="last-name"
                                               placeholder="Тег" required="">
                                    </fieldset>
                                </div>
                            </div>
                            <div class="form-row">
                                <div class="form-holder form-holder-2">
                                    <fieldset>
                                        <legend>Ссылка на видеоурок</legend>
                                        <input type="text" name="your_email" id="your_email" class="form-control"
                                               pattern="[^@]+@[^@]+.[a-zA-Z]{2,6}" placeholder="example.com"
                                               required="">
                                    </fieldset>
                                </div>
                            </div>
                            <div class="form-row">
                                <div class="form-holder form-holder-2">
                                    <fieldset>
                                        <legend>Описание</legend>
                                        <input type="text" class="form-control" id="phone" name="phone"
                                               placeholder="Описание курса" required="">
                                    </fieldset>
                                </div>
                            </div>
                            <div class="form-row form-row-date">
                                <div class="form-holder form-holder-2">
                                    <label class="special-label">Birth Date:</label>
                                    <select name="month" id="month">
                                        <option value="MM" disabled="" selected="">MM</option>
                                        <option value="16">16</option>
                                        <option value="17">17</option>
                                        <option value="18">18</option>
                                        <option value="19">19</option>
                                    </select>
                                    <select name="date" id="date">
                                        <option value="DD" disabled="" selected="">DD</option>
                                        <option value="Feb">Feb</option>
                                        <option value="Mar">Mar</option>
                                        <option value="Apr">Apr</option>
                                        <option value="May">May</option>
                                    </select>
                                    <select name="year" id="year">
                                        <option value="YYYY" disabled="" selected="">YYYY</option>
                                        <option value="2017">2017</option>
                                        <option value="2016">2016</option>
                                        <option value="2015">2015</option>
                                        <option value="2014">2014</option>
                                        <option value="2013">2013</option>
                                    </select>
                                </div>
                            </div>
                            <div class="form-row">
                                <div class="form-holder form-holder-2">
                                    <input type="text" class="form-control input-border" id="ssn" name="ssn"
                                           placeholder="SSN" required="">
                                </div>
                            </div>
                        </div>
                    </section>

                    <h2 id="form-total-h-1" tabindex="-1" class="title">
                        <p class="step-icon"><span>02</span></p>
                        <span class="step-text">Connect Bank Account</span>
                    </h2>
                    <section id="form-total-p-1" role="tabpanel" aria-labelledby="form-total-h-1" class="body"
                             aria-hidden="true" style="display: none;">
                        <div class="inner">
                            <div class="wizard-header">
                                <h3 class="heading">Выберите тематику вашего курса</h3>
                                <p>Из предложенных ниже карточек выберите наиболее подходящую для вашего курса или укажите иной вариант в поле выше</p>
                            </div>
                            <div class="form-row">
                                <div class="form-holder form-holder-1">
                                    <input type="text" name="find_bank" id="find_bank" placeholder="Укажите тематику вашего курса"
                                           class="form-control" required="">
                                </div>
                            </div>
                            <div class="form-row-total">
                                <div class="form-row">
                                    <div class="form-holder form-holder-2 form-holder-3">
                                        <input type="radio" class="radio" name="bank-1" id="bank-1" value="bank-1"
                                               checked="">
                                        <label class="bank-images label-above bank-1-label" for="bank-1">

                                        </label>
                                        <input type="radio" class="radio" name="bank-2" id="bank-2" value="bank-2">
                                        <label class="bank-images label-above bank-2-label" for="bank-2">

                                        </label>
                                        <input type="radio" class="radio" name="bank-3" id="bank-3" value="bank-3">
                                        <label class="bank-images label-above bank-3-label" for="bank-3">

                                        </label>
                                    </div>
                                </div>
                                <div class="form-row">
                                    <div class="form-holder form-holder-2 form-holder-3">
                                        <input type="radio" class="radio" name="bank-4" id="bank-4" value="bank-4">
                                        <label class="bank-images bank-4-label" for="bank-4">

                                        </label>
                                        <input type="radio" class="radio" name="bank-5" id="bank-5" value="bank-5">
                                        <label class="bank-images bank-5-label" for="bank-5">

                                        </label>
                                        <input type="radio" class="radio" name="bank-6" id="bank-6" value="bank-6">
                                        <label class="bank-images bank-6-label" for="bank-6">

                                        </label>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </section>

                    <h2 id="form-total-h-2" tabindex="-1" class="title">
                        <p class="step-icon"><span>03</span></p>
                        <span class="step-text">Set Financial Goals</span>
                    </h2>
                    <section id="form-total-p-2" role="tabpanel" aria-labelledby="form-total-h-2" class="body"
                             aria-hidden="true" style="display: none;">
                        <div class="inner">
                            <div class="wizard-header">
                                <h3 class="heading">Выберите уровень сложности для вашего курса</h3>
                            </div>
                            <div class="form-row">
                                <div class="form-holder form-holder-2">
                                    <input type="radio" class="radio" name="radio1" id="plan-1" value="plan-1">
                                    <label class="plan-icon plan-1-label" for="plan-1">

                                    </label>
                                    <div class="plan-total">
                                        <span class="plan-title">Школьный уровень</span>
                                        <p class="plan-text">Наиболее простой уровень сложности для понимания основ</p>
                                    </div>
                                    <input type="radio" class="radio" name="radio1" id="plan-2" value="plan-2">
                                    <label class="plan-icon plan-2-label" for="plan-2">

                                    </label>
                                    <div class="plan-total">
                                        <span class="plan-title">Продвинутый уровень</span>
                                        <p class="plan-text">Средний уровень, подходящий для большинства обучающихся. Более углубленное изучение в предметной области</p>
                                    </div>
                                    <input type="radio" class="radio" name="radio1" id="plan-3" value="plan-3"
                                           checked="">
                                    <label class="plan-icon plan-3-label" for="plan-3">

                                    </label>
                                    <div class="plan-total">
                                        <span class="plan-title">Экспертный уровень</span>
                                        <p class="plan-text">Наиболее сложный уровень для полного понимания предметной области на профессиональном уровне</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </section>
                </div>
                <div class="actions clearfix">
                    <ul role="menu" aria-label="Pagination">
                        <li class="disabled" aria-disabled="true" @click="previous">
                            <a href="#previous" role="menuitem">Back Step</a>
                        </li>
                        <li aria-hidden="false" aria-disabled="false" @click="next">
                            <a href="#next" role="menuitem">
                                <i class="zmdi zmdi-arrow-right"/>
                            </a>
                        </li>
                        <li aria-hidden="true" style="display: none;" @click="finish">
                            <a href="#finish" role="menuitem">
                                <i class="zmdi zmdi-check"/>
                            </a>
                        </li>
                    </ul>
                </div>
            </section>
        </form>
    </article>
</template>

<script>

export default {
    name: "Register",
    data() {
        return {
            isInfoDone: false,
            isTagDone: false,
            isPlanDone: false,
            progress: 0
        }
    },
    methods: {
        next: function () {
            if (this.progress < 2) {
                this.progress++;
                if (this.progress === 1) {
                    document.getElementById('form-total-p-0').style.display = "none";
                    document.getElementById('form-total-p-1').style.display = "block";
                } else if (this.progress === 2) {
                    document.getElementById('form-total-p-1').style.display = "none";
                    document.getElementById('form-total-p-2').style.display = "block";
                }
            }
        },
        previous: function () {
            if (this.progress > 0) {
                this.progress--;
                if (this.progress === 1) {
                    document.getElementById('form-total-p-2').style.display = "none";
                    document.getElementById('form-total-p-1').style.display = "block";
                } else if (this.progress === 0) {
                    document.getElementById('form-total-p-1').style.display = "none";
                    document.getElementById('form-total-p-0').style.display = "block";
                }
            }
        },
    },
}
</script>

<style scoped>

.wizard-form {
    width: 820px;
}

.content-back {
    background-color: rgba(255, 255, 255, 0.13);
    backdrop-filter: blur(10px);
    box-shadow: 0 0 40px rgba(8, 7, 16, 0.6);
}

.form-v1-content {
    background: #fff;
    width: 820px;
    box-shadow: 0 8px 20px 0 rgba(0, 0, 0, .15);
    -o-box-shadow: 0 8px 20px 0 rgba(0, 0, 0, .15);
    -ms-box-shadow: 0 8px 20px 0 rgba(0, 0, 0, .15);
    -moz-box-shadow: 0 8px 20px 0 rgba(0, 0, 0, .15);
    -webkit-box-shadow: 0 8px 20px 0 rgba(0, 0, 0, .15);
    border-radius: 10px;
    -o-border-radius: 10px;
    -ms-border-radius: 10px;
    -moz-border-radius: 10px;
    -webkit-border-radius: 10px;
    margin: 145px 0;
    font-family: open sans, sans-serif;
    position: relative;
    display: flex;
    display: -webkit-flex
}

.form-v1-content .wizard-form {
    width: 100%
}

.form-register .vertical {
    display: block;
    width: 100%;
    overflow: hidden;
    border-radius: 10px;
    -o-border-radius: 10px;
    -ms-border-radius: 10px;
    -moz-border-radius: 10px;
    -webkit-border-radius: 10px;
}

.form-register .steps {
    float: left;
    width: 280px;
}

.form-register .steps ul {
    list-style: none;
    padding-left: 0;
    margin: 0
}

.form-register .steps li,
.form-register .steps li.current {
    outline: none;
    -o-outline: none;
    -ms-outline: none;
    -moz-outline: none;
    -webkit-outline: none;
    position: relative
}

.form-register .steps li::after {
    width: 280px;
    height: 1px;
    content: "";
    background: rgba(255, 255, 255, .08);
    position: absolute;
    top: 100%
}

.form-register .steps li .current-info {
    display: none
}

.form-register .steps li a {
    text-decoration: none;
    outline: none;
    -o-outline: none;
    -ms-outline: none;
    -moz-outline: none;
    -webkit-outline: none
}

.form-register .steps li a .title {
    display: flex;
    padding: 15px 25px 15px 35px
}

.form-register .steps li a .title .step-icon {
    width: 40px;
    height: 40px;
    border-radius: 50%;
    -o-border-radius: 50%;
    -ms-border-radius: 50%;
    -moz-border-radius: 50%;
    -webkit-border-radius: 50%;
    background: #ccc;
    position: relative;
    outline: none;
    -o-outline: none;
    -ms-outline: none;
    -moz-outline: none;
    -webkit-outline: none;
    color: #333;
    font-size: 16px;
    margin-right: 15px
}

.form-register .steps li a .step-icon span {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    -o-transform: translate(-50%, -50%);
    -ms-transform: translate(-50%, -50%);
    -moz-transform: translate(-50%, -50%);
    -webkit-transform: translate(-50%, -50%)
}

.form-register .steps li.current a .step-icon,
.form-register .steps li.current a:active .step-icon,
.form-register .steps li.done a .step-icon,
.form-register .steps li.done a:active .step-icon {
    background: #4fab40;
    color: #fff;
    box-shadow: 0 3px 10px 0 rgba(0, 0, 0, .25);
    -o-box-shadow: 0 3px 10px 0 rgba(0, 0, 0, .25);
    -ms-box-shadow: 0 3px 10px 0 rgba(0, 0, 0, .25);
    -moz-box-shadow: 0 3px 10px 0 rgba(0, 0, 0, .25);
    -webkit-box-shadow: 0 3px 10px 0 rgba(0, 0, 0, .25)
}

.form-register .steps li a .step-text {
    color: #ccc;
    font-weight: 600;
    font-size: 15px;
    padding: 25px 0 8px
}

.form-register .steps .current .step-text,
.form-register .steps .done .step-text {
    color: #fff
}

.form-register .content {
    box-shadow: 0 3px 10px 0 rgba(0, 0, 0, .15);
    -o-box-shadow: 0 3px 10px 0 rgba(0, 0, 0, .15);
    -ms-box-shadow: 0 3px 10px 0 rgba(0, 0, 0, .15);
    -moz-box-shadow: 0 3px 10px 0 rgba(0, 0, 0, .15);
    -webkit-box-shadow: 0 3px 10px 0 rgba(0, 0, 0, .15);
    float: right;
    width: 540px;
    background: #fff;
}

.form-register .content h2 {
    display: none
}

.form-register .content .inner {
    padding: 0 50px
}

.form-register .content .wizard-header {
    text-align: center;
    padding: 37px 30px 13px
}

.form-register .content #form-total-p-2 .wizard-header {
    text-align: center;
    padding: 37px 30px 30px
}

.form-register .content .inner h3 {
    font-size: 22px;
    color: #333;
    font-weight: 700;
    margin: 0
}

.form-register .content .inner p {
    color: #666;
    font-size: 14px;
    font-weight: 600
}

.inner .form-row-total {
    box-shadow: 0 3px 10px 0 rgba(0, 0, 0, .15);
    -o-box-shadow: 0 3px 10px 0 rgba(0, 0, 0, .15);
    -ms-box-shadow: 0 3px 10px 0 rgba(0, 0, 0, .15);
    -moz-box-shadow: 0 3px 10px 0 rgba(0, 0, 0, .15);
    -webkit-box-shadow: 0 3px 10px 0 rgba(0, 0, 0, .15);
    margin-bottom: 40px;
    margin-top: 10px
}

.inner .form-row {
    display: flex;
    margin: 0 -10px;
    position: relative
}

.inner .form-row .form-holder {
    width: 50%;
    padding: 0 10px;
    margin-bottom: 17px;
    position: relative
}

.inner .form-row .form-holder.form-holder-1 {
    width: 65.3%
}

.inner .form-row .form-holder.form-holder-2 {
    width: 100%;
    position: relative
}

.inner .form-row .form-holder.form-holder-3 {
    margin-bottom: 0
}

.inner .form-row .form-row-inner {
    position: relative
}

.inner .form-row #radio {
    margin-top: -5px;
    margin-left: 7px
}

.inner .form-row #checkbox {
    margin: 10px 0 28px 11px;
    font-size: 15px;
    color: #666;
    font-weight: 400
}

.inner .form-row .form-holder label.special-label {
    display: block;
    float: none;
    margin-top: 8px;
    margin-bottom: 15px;
    padding-right: 0;
    color: #666;
    font-size: 16px;
    font-weight: 400
}

.inner .form-row .form-holder fieldset {
    border: 2px solid #e5e5e5;
    border-radius: 4px;
    -moz-border-radius: 4px;
    -webkit-border-radius: 4px;
    -o-border-radius: 4px;
    -ms-border-radius: 4px;
    padding: 0 20px
}

.inner .form-row .form-holder legend {
    font-size: 11px;
    font-weight: 700;
    color: #999
}

.inner .form-row .form-holder input,
.inner .form-row .form-holder select {
    width: 100%;
    padding: 5px 0 13px;
    border: none;
    appearance: unset;
    -moz-appearance: unset;
    -webkit-appearance: unset;
    -o-appearance: unset;
    -ms-appearance: unset;
    outline: none;
    -moz-outline: none;
    -webkit-outline: none;
    -o-outline: none;
    -ms-outline: none;
    font-family: open sans, sans-serif;
    font-weight: 600;
    font-size: 14px;
    box-sizing: border-box;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    -o-box-sizing: border-box;
    -ms-box-sizing: border-box;
    border-radius: 4px;
    -moz-border-radius: 4px;
    -webkit-border-radius: 4px;
    -o-border-radius: 4px;
    -ms-border-radius: 4px
}

.inner .form-row .form-holder input {
    color: #333
}

.inner .form-row .form-holder input#find_bank {
    border: 2px solid #e5e5e5;
    padding: 11px 20px
}

.inner .form-row .form-holder input.radio {
    display: none
}

.inner .form-row-total label {
    width: 146.5px;
    height: 130px;
    display: block;
    cursor: pointer;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    -o-box-sizing: border-box;
    -ms-box-sizing: border-box;
    box-sizing: border-box;
    float: left;
    text-align: center
}

.inner .form-row-total label img {
    padding-top: 25px
}

.inner .form-row-total .label-above {
    border-bottom: 1px solid #e5e5e5
}

.inner .form-row-total .bank-1-label,
.inner .form-row-total .bank-2-label,
.inner .form-row-total .bank-4-label,
.inner .form-row-total .bank-5-label {
    border-right: 1px solid #e5e5e5
}

.inner .form-row-total input#bank-1:checked + label,
.inner .form-row-total input#bank-2:checked + label,
.inner .form-row-total input#bank-3:checked + label,
.inner .form-row-total input#bank-4:checked + label,
.inner .form-row-total input#bank-5:checked + label,
.inner .form-row-total input#bank-6:checked + label {
    border: none;
    box-shadow: 0 3px 10px 0 rgba(0, 0, 0, .15);
    -o-box-shadow: 0 3px 10px 0 rgba(0, 0, 0, .15);
    -ms-box-shadow: 0 3px 10px 0 rgba(0, 0, 0, .15);
    -moz-box-shadow: 0 3px 10px 0 rgba(0, 0, 0, .15);
    -webkit-box-shadow: 0 3px 10px 0 rgba(0, 0, 0, .15)
}

.inner .form-row .form-holder .plan-icon {
    background: #999;
    width: 65px;
    height: 65px;
    border-radius: 50%;
    -o-border-radius: 50%;
    -ms-border-radius: 50%;
    -moz-border-radius: 50%;
    -webkit-border-radius: 50%;
    position: relative;
    float: left;
    margin-right: 23px;
    margin-top: -4px;
    cursor: pointer
}

.inner .form-row .form-holder .plan-icon img {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    -o-transform: translate(-50%, -50%);
    -ms-transform: translate(-50%, -50%);
    -moz-transform: translate(-50%, -50%);
    -webkit-transform: translate(-50%, -50%)
}

.inner .form-row .form-holder .plan-total {
    margin-bottom: 55px
}

.inner .form-row .form-holder .plan-total .plan-title {
    font-size: 18px;
    color: #333;
    font-weight: 700
}

.inner .form-row .form-holder .plan-total .plan-text {
    font-size: 14px;
    color: #666;
    font-weight: 600;
    margin: 0;
    padding-top: 5px
}

.inner .form-row .form-holder input#plan-1:checked + label,
.inner .form-row .form-holder input#plan-2:checked + label,
.inner .form-row .form-holder input#plan-3:checked + label {
    background: #4fab40
}

.inner .form-row .form-holder select {
    font-size: 14px;
    color: #666;
    font-weight: 600;
    background: #fff url(../images/form-v1-icon.png) no-repeat scroll;
    background-position: right 6px center;
    z-index: 1;
    cursor: pointer;
    position: relative;
    border: 2px solid #e5e5e5;
    padding: 10.4px 13px
}

.inner .form-row .form-holder .input-border {
    border: 2px solid #e5e5e5;
    padding: 11px 20px;
    margin-top: 8px
}

.inner .form-row.form-row-date .form-holder select {
    float: left;
    width: 20.6%;
    margin-right: 15px
}

.inner .form-row.form-row-date .form-holder select#year {
    width: 27.28%
}

.inner .form-row .form-holder input::-webkit-input-placeholder {
    color: #666;
    font-size: 14px
}

.inner .form-row .form-holder input::-moz-placeholder {
    color: #666;
    font-size: 14px
}

.inner .form-row .form-holder input:-ms-input-placeholder {
    color: #666;
    font-size: 14px
}

.inner .form-row .form-holder input:-moz-placeholder {
    color: #666;
    font-size: 14px
}

.actions {
    float: right;
    width: 540px;
    background: #fff;
}

.actions ul {
    list-style: none;
    padding: 0 50px;
    margin: 13px 0 35px;
    display: flex;
    display: -webkit-flex;
    justify-content: space-between;
    -o-justify-content: space-between;
    -ms-justify-content: space-between;
    -moz-justify-content: space-between;
    -webkit-justify-content: space-between
}

.actions ul li.disabled,
.actions ul li:first-child {
    opacity: 0
}

.actions ul li {
    padding: 0;
    border: none;
    border-radius: 50%;
    -o-border-radius: 50%;
    -ms-border-radius: 50%;
    -moz-border-radius: 50%;
    -webkit-border-radius: 50%;
    display: inline-flex;
    height: 50px;
    width: 50px;
    justify-content: center;
    -o-justify-content: center;
    -ms-justify-content: center;
    -moz-justify-content: center;
    -webkit-justify-content: center;
    align-items: center;
    -o-align-items: center;
    -ms-align-items: center;
    -moz-align-items: center;
    -webkit-align-items: center;
    background: #4fab40;
    cursor: pointer;
    font-size: 18px
}

.actions ul li:hover {
    background: #36782c
}

.actions ul li a {
    color: #fff;
    text-decoration: none;
    padding: 13px 19px
}

@media screen and (max-width: 1199px) {
    .form-v1-content {
        margin: 180px 20px
    }
}

@media screen and (max-width: 991px) {
    .form-register .vertical {
        background: #fff
    }

    .form-register .steps,
    .form-register .content,
    .actions {
        float: none;
        width: 100%
    }

    .form-register .content,
    .inner .form-row-total {
        box-shadow: none;
        -o-box-shadow: none;
        -ms-box-shadow: none;
        -moz-box-shadow: none;
        -webkit-box-shadow: none
    }

    .form-register .steps li a .title {
        justify-content: space-between;
        -o-justify-content: space-between;
        -ms-justify-content: space-between;
        -moz-justify-content: space-between;
        -webkit-justify-content: space-between
    }

    .form-register .steps li::after {
        width: 100%
    }

    .inner .form-row .form-holder.form-holder-3 {
        margin-bottom: 20px
    }

    .inner .form-row-total label {
        margin-right: 20px;
        border: 1px solid #e5e5e5
    }
}

@media screen and (max-width: 767px) and (min-width: 576px) {
    .inner .form-row-total label {
        width: 120px
    }
}

@media screen and (max-width: 767px) {
    .inner .form-row.form-row-date .form-holder select {
        width: 17.5%;
        margin-right: 20px
    }
}

@media screen and (max-width: 575px) {
    .form-register .content .inner {
        padding: 0 30px
    }

    .form-register .content .wizard-header,
    .form-register .content #form-total-p-2 .wizard-header {
        padding: 37px 0 13px
    }

    .inner .form-row {
        flex-direction: column;
        -o-flex-direction: column;
        -ms-flex-direction: column;
        -moz-flex-direction: column;
        -webkit-flex-direction: column;
        margin: 0
    }

    .inner .form-row .form-holder {
        width: 100%
    }

    .inner .form-row .form-holder.form-holder-1 {
        width: 100%
    }

    .inner .form-row .form-holder {
        padding: 0
    }

    .inner .form-row.form-row-date .form-holder select#year,
    .inner .form-row.form-row-date .form-holder select {
        width: 100%;
        margin-bottom: 20px
    }

    .inner .form-row .form-holder .plan-icon {
        margin-top: 4px
    }

    .inner .form-row .form-holder .plan-total {
        margin-left: 90px
    }

    .inner .form-row-total label {
        margin-bottom: 20px
    }

    .inner .form-row .form-holder.form-holder-3 {
        margin-bottom: 0
    }
}
</style>