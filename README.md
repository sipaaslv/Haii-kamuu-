# Halloo sayangnyaa akuu❤️
Aku punyaa sesuatu buat kamu
Jawab jujur ya sayangg hehe
Awass kaloo boong, akumah marahh. 

        const {
          nilai: Fauzansf
        } = Swal.fire ({
          judul: 'Isii namamuu yaaa',
          Masukkan teks' Fauzansf
          inputLabel: '',
          showCancelButton: benar,
          inputValidator: (nilai) => {
            if (! value) {
              return 'isi duluu dongg byy :('
            } lain {
              nama = Fauzansf
            }
          }
        }). kemudian (function () {
          pertanyaan const = Swal.fire ({
            title: `$ {nama} kamuu sayang ga sama $ {sender}?`,
            showDenyButton: benar,
            showCancelButton: false,
            confirmButtonText: `Sayang bangett`,
            denyButtonText: `Nggak sayang`,
          }). lalu ((hasil) => {
            / * Baca selengkapnya tentang isConfirmed, isDenied di bawah * /
            if (result.isConfirmed) {
              Swal.fire (`$ {sender} juga sayang banget sama $ {nama}`). Lalu (function () {
                Swal.fire ({
                  title: 'Seberapa sayang emangnya?',
                  ikon: 'pertanyaan',
                  masukan: 'range',
                  inputLabel: 'Antara satu sampai seratus ya',
                  inputAttributes: {
                    min: 1,
                    maks: 100,
                    Langkah 1
                  },
                  inputValue: 50
                }). lalu ((e) => {
                  val = e.value
                  Swal.fire (`Makasih banget ya byy udah sayang sama $ {sender} $ {val}%`) .then (function () {
                    Swal.fire ({
                      title: `Sekarang $ {nama} kangen ga sama $ {sender}?`,
                      showDenyButton: benar,
                      showCancelButton: false,
                      confirmButtonText: `Kangen: (`,
                      denyButtonText: `Nggak:)`,
                    }). lalu ((hasil) => {
                      / * Baca selengkapnya tentang isConfirmed, isDenied di bawah * /
                      if (result.isConfirmed) {
                        Swal.fire (`Huhuhuhuhuhu iya $ {sender} juga kangen bangett samaaa $ {nama}, makasihhh yaa:)`). Lalu (function () {
                          Swal.fire ('Kali ini terakhir dehh :)'). Then (function () {
                            Swal.fire ('Coba tolong klik ikon hati di paling bawah dong')
                          })
                        })
                      } lain jika (result.isDenied) {
                        Swal.fire ('yahhh, emang ga kangen apaa sama pacar sendiri :(', '', 'error'). Then (function () {
                          Swal.fire ('Yaudaaa dehhh: ((')
                        })
                      }
                    })
                  })
                })
              })
            } lain jika (result.isDenied) {
              Swal.fire (`` Yakin kamu ga sayang sama $ {sender}? `, '', 'Error'). Then (function () {
                Swal.fire ('Ok deh: ((')
