/* =========================================================
   CLICK REPAROS — JAVASCRIPT V2
   ========================================================= */

const WHATSAPP = "5521967358108";

const services = {
  hidraulica: [
    "Vazamento de torneira",
    "Vazamento de cano",
    "Troca de torneira",
    "Troca de sifão",
    "Conserto de descarga",
    "Troca de registro",
    "Reparo em pia",
    "Desentupimento",
    "Instalação de caixa d'água",
    "Manutenção hidráulica"
  ],

  eletrica: [
    "Instalação de tomada",
    "Instalação de interruptor",
    "Troca de disjuntor",
    "Reparo elétrico",
    "Instalação de chuveiro",
    "Instalação de luminária",
    "Instalação de ventilador de teto",
    "Reparo de fiação",
    "Curto-circuito",
    "Manutenção elétrica"
  ],

  instalacoes: [
    "Instalação de suporte de TV",
    "Instalação de prateleira",
    "Instalação de cortina",
    "Instalação de espelho",
    "Instalação de varal",
    "Instalação de fechadura",
    "Montagem de móveis",
    "Instalação de eletrodomésticos",
    "Fixação de objetos",
    "Outras instalações"
  ],

  pintura: [
    "Pintura de parede",
    "Retoque de pintura",
    "Reparo em parede",
    "Reparo de trinca",
    "Reparo de infiltração",
    "Aplicação de rejunte",
    "Reparo em gesso",
    "Troca de azulejo",
    "Troca de piso",
    "Pequenos reparos"
  ]
};


/* =========================================================
   ELEMENTOS
   ========================================================= */

const serviceSelect = document.querySelector("#service");
const categoryButtons = document.querySelectorAll("[data-category]");
const budgetForm = document.querySelector("#budgetForm");
const whatsappButtons = document.querySelectorAll("[data-whatsapp]");


/* =========================================================
   WHATSAPP
   ========================================================= */

function openWhatsApp(message = "") {

  const encodedMessage = encodeURIComponent(message);

  const url = `https://wa.me/${WHATSAPP}?text=${encodedMessage}`;

  window.open(url, "_blank");
}


/* =========================================================
   CTA PRINCIPAL
   ========================================================= */

whatsappButtons.forEach(button => {

  button.addEventListener("click", function(event) {

    event.preventDefault();

    const message =
      "Olá! Vim pelo site da Click Reparos e preciso de um orçamento. " +
      "Gostaria de saber como funciona o atendimento.";

    openWhatsApp(message);

  });

});


/* =========================================================
   CATEGORIAS
   ========================================================= */

function showCategory(category) {

  if (!serviceSelect) return;

  serviceSelect.innerHTML =
    '<option value="">Selecione o que você precisa</option>';

  if (!services[category]) return;

  services[category].forEach(service => {

    const option = document.createElement("option");

    option.value = service;
    option.textContent = service;

    serviceSelect.appendChild(option);

  });

}


/* =========================================================
   BOTÕES DAS CATEGORIAS
   ========================================================= */

categoryButtons.forEach(button => {

  button.addEventListener("click", function() {

    const category = this.dataset.category;

    showCategory(category);

    const formSection =
      document.querySelector("#orcamento");

    if (formSection) {

      formSection.scrollIntoView({
        behavior: "smooth",
        block: "start"
      });

    }

  });

});


/* =========================================================
   FORMULÁRIO DE ORÇAMENTO
   ========================================================= */

if (budgetForm) {

  budgetForm.addEventListener("submit", function(event) {

    event.preventDefault();

    const name =
      document.querySelector("#name")?.value.trim() || "";

    const phone =
      document.querySelector("#phone")?.value.trim() || "";

    const neighborhood =
      document.querySelector("#neighborhood")?.value.trim() || "";

    const address =
      document.querySelector("#address")?.value.trim() || "";

    const service =
      document.querySelector("#service")?.value.trim() || "";

    const details =
      document.querySelector("#details")?.value.trim() || "";


    if (!name) {

      alert("Por favor, informe seu nome.");

      return;

    }


    if (!neighborhood) {

      alert("Por favor, informe seu bairro.");

      return;

    }


    if (!service) {

      alert("Selecione o serviço que você precisa.");

      return;

    }


    let message =
      `Olá! Sou ${name} e gostaria de solicitar um orçamento com a Click Reparos.%0A%0A`;

    message =
      `Olá! Sou ${name} e gostaria de solicitar um orçamento com a Click Reparos.\n\n`;

    message += `🔧 Serviço: ${service}\n`;

    if (phone) {
      message += `📱 Meu WhatsApp: ${phone}\n`;
    }

    message += `📍 Bairro: ${neighborhood}\n`;

    if (address) {
      message += `🏠 Endereço: ${address}\n`;
    }

    if (details) {
      message += `\n📝 Sobre o serviço:\n${details}\n`;
    }

    message +=
      "\n📷 Posso enviar fotos ou vídeos do serviço, se necessário.";


    openWhatsApp(message);

  });

}


/* =========================================================
   MÁSCARA DE TELEFONE
   ========================================================= */

const phoneInput = document.querySelector("#phone");

if (phoneInput) {

  phoneInput.addEventListener("input", function() {

    let value = this.value.replace(/\D/g, "");

    if (value.length > 11) {
      value = value.substring(0, 11);
    }

    if (value.length <= 10) {

      value = value.replace(
        /^(\d{2})(\d{4})(\d{0,4}).*/,
        "($1) $2-$3"
      );

    } else {

      value = value.replace(
        /^(\d{2})(\d{5})(\d{0,4}).*/,
        "($1) $2-$3"
      );

    }

    this.value = value;

  });

}


/* =========================================================
   MENU MOBILE
   ========================================================= */

const menuButton =
  document.querySelector("#menuButton");

const mobileMenu =
  document.querySelector("#mobileMenu");

if (menuButton && mobileMenu) {

  menuButton.addEventListener("click", function() {

    mobileMenu.classList.toggle("active");

  });


  mobileMenu.querySelectorAll("a").forEach(link => {

    link.addEventListener("click", function() {

      mobileMenu.classList.remove("active");

    });

  });

}


/* =========================================================
   SCROLL SUAVE
   ========================================================= */

document.querySelectorAll('a[href^="#"]').forEach(link => {

  link.addEventListener("click", function(event) {

    const targetId =
      this.getAttribute("href");

    if (!targetId || targetId === "#") return;

    const target =
      document.querySelector(targetId);

    if (!target) return;

    event.preventDefault();

    target.scrollIntoView({
      behavior: "smooth",
      block: "start"
    });

  });

});


/* =========================================================
   BOTÃO FLUTUANTE DO WHATSAPP
   ========================================================= */

const floatingWhatsApp =
  document.querySelector("#floatingWhatsApp");

if (floatingWhatsApp) {

  floatingWhatsApp.addEventListener("click", function(event) {

    event.preventDefault();

    const message =
      "Olá! Vim pelo site da Click Reparos. Preciso de ajuda com um reparo e gostaria de solicitar um orçamento.";

    openWhatsApp(message);

  });

}


/* =========================================================
   ANO AUTOMÁTICO NO RODAPÉ
   ========================================================= */

const yearElements =
  document.querySelectorAll("[data-year]");

yearElements.forEach(element => {

  element.textContent =
    new Date().getFullYear();

});


/* =========================================================
   ANIMAÇÃO DE ENTRADA
   ========================================================= */

const animatedElements =
  document.querySelectorAll(".reveal");

if ("IntersectionObserver" in window) {

  const observer =
    new IntersectionObserver(
      entries => {

        entries.forEach(entry => {

          if (entry.isIntersecting) {

            entry.target.classList.add("visible");

            observer.unobserve(entry.target);

          }

        });

      },
      {
        threshold: 0.12
      }
    );


  animatedElements.forEach(element => {

    observer.observe(element);

  });

}


/* =========================================================
   CONSOLE
   ========================================================= */

console.log(
  "Click Reparos — site carregado com sucesso."
);
