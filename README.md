# APP-TEROR-FILM-FEST-2026
Aplicación del festival de cine internacional TEROR FILM FEST
import { FestivalNewsItem, ParticipantProfile, CommunityPost, FilmingLocation } from '../types';

export const OFFICIAL_PASSCODES = ['CINE2025', 'FESTIVAL2025', 'FESTIVAL', 'CINE'];

export const CINEMA_PROFESSIONS = [
  'Dirección de Cine',
  'Guion y Dramaturgia',
  'Producción Audiovisual',
  'Dirección de Fotografía',
  'Actuación / Elenco',
  'Montaje y Edición',
  'Diseño de Sonido y Composición',
  'Dirección de Arte y Vestuario',
  'Efectos Visuales (VFX) y Animación',
  'Crítica Cinematográfica / Prensa',
  'Estudiante de Cine / Audiovisuales',
  'Distribución y Festivales'
];

export const INITIAL_NEWS: FestivalNewsItem[] = [
  {
    id: 'news-1',
    title: 'Gala de Apertura: Proyección especial y alfombra roja de bienvenida',
    category: 'anuncios',
    categoryLabel: 'Anuncio Oficial',
    summary: 'Inauguración oficial de la 18ª edición del Festival Internacional de Cine con presencia del jurado internacional.',
    content: 'Damos la bienvenida a todos los cineastas acreditados a la ceremonia de apertura en el Gran Teatro Central. Tras la recepción en la alfombra roja, se proyectará la película de estreno mundial y se ofrecerá el cóctel inaugural con el jurado y patrocinadores.',
    date: '15 Octubre, 2025',
    time: '19:30 - 22:00',
    location: 'Gran Teatro Central (Sala Principal)',
    badge: 'Destacado',
    likes: 42
  },
  {
    id: 'news-2',
    title: 'Masterclass: "La mirada cinematográfica en el cine contemporáneo"',
    category: 'masterclasses',
    categoryLabel: 'Masterclass',
    summary: 'Encuentro exclusivo con la reconocida directora ganadora en Cannes sobre dirección de actores y puesta en escena.',
    content: 'Una sesión intensiva de dos horas explorando el diseño visual, el trabajo con actores no profesionales y la construcción del tiempo dramático. Los participantes acreditados tendrán prioridad de acceso y ronda de preguntas.',
    date: '16 Octubre, 2025',
    time: '11:00 - 13:00',
    location: 'Aula Magna - Centro Audiovisual',
    badge: 'Cupo Limitado',
    likes: 68
  },
  {
    id: 'news-3',
    title: 'Sección Oficial en Competencia: Cortometrajes de Ficción',
    category: 'proyecciones',
    categoryLabel: 'Proyecciones',
    summary: 'Primer bloque de cortometrajes seleccionados para el premio Ojo de Oro con debate posterior con sus directores.',
    content: 'Presentación de 6 obras procedentes de España, Iberoamérica y Europa, abordando narrativas de memoria, identidad y género. Habrá sesión de preguntas y respuestas (Q&A) de 30 minutos al finalizar la sesión.',
    date: '16 Octubre, 2025',
    time: '16:30 - 18:45',
    location: 'Cine Capitol - Sala 2 (Kubrick)',
    badge: 'Competencia',
    likes: 35
  },
  {
    id: 'news-4',
    title: 'Encuentro de Coproducción y Encuentros Profesionales: Pitching & Café',
    category: 'anuncios',
    categoryLabel: 'Industria & Encuentros',
    summary: 'Espacio distendido para conectar productores, directores noveles y guionistas en busca de alianzas.',
    content: 'Espacio de conexión profesional donde directores y guionistas acreditados pueden presentar proyectos en desarrollo en formato speed-pitching de 5 minutos ante productoras independientes invitadas.',
    date: '17 Octubre, 2025',
    time: '10:00 - 12:30',
    location: 'Terraza Panorama del Festival',
    badge: 'Industria',
    likes: 54
  },
  {
    id: 'news-5',
    title: 'Anuncio del Jurado: Reveladas las bases y premios de esta edición',
    category: 'premios',
    categoryLabel: 'Premios & Jurado',
    summary: 'Detalles sobre los galardones Ojo de Oro, Mejor Guion, Premio de la Crítica y Premio del Público.',
    content: 'El comité directivo ha publicado el desglose de estatuillas y dotaciones para la Gala de Clausura. Todos los acreditados tienen derecho a votar en la urna digital para el Premio del Público durante las sesiones oficiales.',
    date: '18 Octubre, 2025',
    time: '12:00',
    location: 'Pabellón de Prensa & Online',
    badge: 'Premios',
    likes: 29
  }
];

export const INITIAL_PARTICIPANTS: ParticipantProfile[] = [
  {
    id: 'part-1',
    fullName: 'Clara Domínguez',
    age: 28,
    profession: 'Dirección de Cine',
    bio: 'Directora y montadora. Presentando el cortometraje "Sombras del Mar" en la sección Nuevos Talentos. Apasionada por el cine de autor y las narrativas intimistas.',
    avatarUrl: 'https://images.unsplash.com/photo-1534528741775-53994a69daeb?w=400&auto=format&fit=crop&q=80',
    socialLinks: {
      instagram: 'https://instagram.com/claradom.cine',
      vimeoOrShowreel: 'https://vimeo.com/claradominguez',
      imdb: 'https://imdb.com/name/nm10928374',
      linkedin: 'https://linkedin.com/in/claradominguez-dir'
    },
    accreditationNumber: 'FC-2025-0142',
    passType: 'Cineasta Seleccionado',
    registeredAt: '2025-10-01'
  },
  {
    id: 'part-2',
    fullName: 'Mateo Arismendi',
    age: 33,
    profession: 'Dirección de Fotografía',
    bio: 'Director de Fotografía con 8 años de experiencia en documental y ficción. Trabajo con ARRI Alexa Mini y ópticas vintage. Busco conectar con directores para proyectos de largometraje en 2026.',
    avatarUrl: 'https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=400&auto=format&fit=crop&q=80',
    socialLinks: {
      instagram: 'https://instagram.com/mateo.dop',
      vimeoOrShowreel: 'https://vimeo.com/mateoarismendi',
      website: 'https://mateoarismendi.com'
    },
    accreditationNumber: 'FC-2025-0189',
    passType: 'Participante Oficial',
    registeredAt: '2025-10-03'
  },
  {
    id: 'part-3',
    fullName: 'Lucía Benítez Mora',
    age: 26,
    profession: 'Guion y Dramaturgia',
    bio: 'Guionista de ficción y thriller psicológico. Dos obras seleccionadas en laboratorios de desarrollo Iberoamericanos. Disponible para consultoría de guiones y colaboraciones.',
    avatarUrl: 'https://images.unsplash.com/photo-1494790108377-be9c29b29330?w=400&auto=format&fit=crop&q=80',
    socialLinks: {
      twitter: 'https://twitter.com/luciab_script',
      linkedin: 'https://linkedin.com/in/luciabenitezmora',
      imdb: 'https://imdb.com/name/nm9823120'
    },
    accreditationNumber: 'FC-2025-0211',
    passType: 'Participante Oficial',
    registeredAt: '2025-10-04'
  },
  {
    id: 'part-4',
    fullName: 'David Salgado',
    age: 36,
    profession: 'Producción Audiovisual',
    bio: 'Productor en Lumbre Cine. Enfocado en coproducciones internacionales España - Latinoamérica. Interesado en proyectos con fuerte identidad visual y contenido social.',
    avatarUrl: 'https://images.unsplash.com/photo-1500648767791-00dcc994a43e?w=400&auto=format&fit=crop&q=80',
    socialLinks: {
      linkedin: 'https://linkedin.com/in/davidsalgadoprod',
      website: 'https://lumbrecine.com',
      instagram: 'https://instagram.com/davidsalgado_prod'
    },
    accreditationNumber: 'FC-2025-0087',
    passType: 'Industria / Productor',
    registeredAt: '2025-09-28'
  },
  {
    id: 'part-5',
    fullName: 'Alba Serrano',
    age: 29,
    profession: 'Diseño de Sonido y Composición',
    bio: 'Compositora de bandas sonoras y diseñadora de sonido envolvente (Dolby Atmos). Apasionada por texturas analógicas y música electroacústica para cine.',
    avatarUrl: 'https://images.unsplash.com/photo-1517841905240-472988babdf9?w=400&auto=format&fit=crop&q=80',
    socialLinks: {
      vimeoOrShowreel: 'https://soundcloud.com/albaserrano-sound',
      instagram: 'https://instagram.com/alba.soundtrack',
      website: 'https://albaserrano.art'
    },
    accreditationNumber: 'FC-2025-0294',
    passType: 'Participante Oficial',
    registeredAt: '2025-10-05'
  }
];

export const INITIAL_POSTS: CommunityPost[] = [
  {
    id: 'post-1',
    authorId: 'part-2',
    authorName: 'Mateo Arismendi',
    authorProfession: 'Dirección de Fotografía',
    authorAvatar: 'https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=400&auto=format&fit=crop&q=80',
    content: '¡Hola a todos! Estaré toda la tarde en la Terraza Panorama con muestras de planos rodados en 16mm. Si algún director o guionista quiere charlar sobre tratamiento visual para futuros proyectos, ¡acérquense a tomar un café!',
    tag: 'Punto de Encuentro',
    timestamp: 'Hace 45 min',
    likes: 12,
    commentsCount: 4
  },
  {
    id: 'post-2',
    authorId: 'part-1',
    authorName: 'Clara Domínguez',
    authorProfession: 'Dirección de Cine',
    authorAvatar: 'https://images.unsplash.com/photo-1534528741775-53994a69daeb?w=400&auto=format&fit=crop&q=80',
    content: '¿Alguien tiene entradas o acceso a la sesión de debate con el jurado de las 18h? Estamos armando un grupo de directores noveles para sentarnos juntos e intercambiar impresiones al salir.',
    tag: 'Debate',
    timestamp: 'Hace 2 horas',
    likes: 8,
    commentsCount: 6
  },
  {
    id: 'post-3',
    authorId: 'part-4',
    authorName: 'David Salgado',
    authorProfession: 'Producción Audiovisual',
    authorAvatar: 'https://images.unsplash.com/photo-1500648767791-00dcc994a43e?w=400&auto=format&fit=crop&q=80',
    content: 'Convocatoria abierta: Buscamos guiones de cortometraje de género fantástico o thriller para postular a fondos de desarrollo de otoño. Podéis escribirme por mensaje privado en esta app o dejarme vuestro portfolio.',
    tag: 'Colaboración',
    timestamp: 'Hace 4 horas',
    likes: 21,
    commentsCount: 9
  }
];

export const INITIAL_FILMING_LOCATIONS: FilmingLocation[] = [
  {
    id: 'loc-1',
    title: 'Palacio Señorial de los Condes de Altamira',
    category: 'historico',
    categoryLabel: 'Patrimonio Histórico',
    address: 'Calle de la Palma 42, 28004 Madrid',
    city: 'Madrid',
    postalCode: '28004',
    description: 'Impresionante palacete del siglo XVIII con patio de columnas de granito, escalinata de mármol imperial y salones de techos artesonados. Excelente conservación para producciones de época, dramas históricos o thrillers aristocráticos.',
    photos: [
      'https://images.unsplash.com/photo-1513694203232-719a280e022f?w=1200&auto=format&fit=crop&q=80',
      'https://images.unsplash.com/photo-1582533561751-ef6f6ab93a2e?w=1200&auto=format&fit=crop&q=80',
      'https://images.unsplash.com/photo-1600585154340-be6161a56a0c?w=1200&auto=format&fit=crop&q=80'
    ],
    googleMapsUrl: 'https://www.google.com/maps/search/?api=1&query=Calle+de+la+Palma+42+Madrid',
    directionsUrl: 'https://www.google.com/maps/dir/?api=1&destination=Calle+de+la+Palma+42+Madrid',
    permitInfo: 'Gestión con la Film Commission municipal. Se requiere seguro de responsabilidad civil y solicitud con 10 días de antelación.',
    scoutingNotes: {
      soundConditions: 'Silencioso (ideal sonido directo)',
      powerSupply: 'Toma trifásica de 63A en cuadro principal de planta baja',
      bestLightTime: 'Luz matinal filtrada de 09:30 a 13:00 en patio central',
      parkingAccess: 'Reserva de estacionamiento para 3 camiones de producción en calle lateral'
    },
    addedBy: {
      id: 'part-1',
      name: 'Clara Domínguez',
      role: 'Dirección de Cine',
      avatar: 'https://images.unsplash.com/photo-1534528741775-53994a69daeb?w=400&auto=format&fit=crop&q=80'
    },
    createdAt: '12 Octubre, 2025'
  },
  {
    id: 'loc-2',
    title: 'Nave Industrial y Silos de Hormigón "El Dique"',
    category: 'industrial',
    categoryLabel: 'Industrial & Brutalista',
    address: 'Carrer de la Maquinista 88, 08003 Barcelona',
    city: 'Barcelona',
    postalCode: '08003',
    description: 'Complejo industrial en desuso con techos de doble altura, claraboyas de luz cenital dramática, muros de ladrillo visto con textura desgastada y tuberías de acero. Perfecto para cine distópico, acción o escenas de persecución.',
    photos: [
      'https://images.unsplash.com/photo-1565008447742-97f6f38c985c?w=1200&auto=format&fit=crop&q=80',
      'https://images.unsplash.com/photo-1508873696983-2df5293cb32f?w=1200&auto=format&fit=crop&q=80',
      'https://images.unsplash.com/photo-1518640467707-6811f4a6ab73?w=1200&auto=format&fit=crop&q=80'
    ],
    googleMapsUrl: 'https://www.google.com/maps/search/?api=1&query=Carrer+de+la+Maquinista+88+Barcelona',
    directionsUrl: 'https://www.google.com/maps/dir/?api=1&destination=Carrer+de+la+Maquinista+88+Barcelona',
    permitInfo: 'Propiedad privada en alquiler por jornadas. Incluye vigilante de seguridad y llaves 24h.',
    scoutingNotes: {
      soundConditions: 'Moderado (ruido urbano controlable)',
      powerSupply: 'Requiere generador auxiliar o enganche provisional de alta potencia',
      bestLightTime: 'Haz de luz cenital espectacular de 14:00 a 17:30',
      parkingAccess: 'Patio interior privado con espacio para hasta 6 camiones y caravana de vestuario'
    },
    addedBy: {
      id: 'part-2',
      name: 'Mateo Arismendi',
      role: 'Dirección de Fotografía',
      avatar: 'https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=400&auto=format&fit=crop&q=80'
    },
    createdAt: '11 Octubre, 2025'
  },
  {
    id: 'loc-3',
    title: 'Acantilados Negros y Cala de Roca Volcánica',
    category: 'costero',
    categoryLabel: 'Costero & Marítimo',
    address: 'Paseo del Faro s/n, 38683 Santiago del Teide, Santa Cruz de Tenerife',
    city: 'Tenerife',
    postalCode: '38683',
    description: 'Paredes verticales de roca basáltica de más de 300 metros sobre el océano Atlántico, con oleaje rompiendo contra plataformas de lava oscura. Atmósfera imponente de misterio salvaje, ciencia ficción cósmica o drama íntimo frente al mar.',
    photos: [
      'https://images.unsplash.com/photo-1507525428034-b723cf961d3e?w=1200&auto=format&fit=crop&q=80',
      'https://images.unsplash.com/photo-1519046904884-53103b34b206?w=1200&auto=format&fit=crop&q=80',
      'https://images.unsplash.com/photo-1471922694855-fa59acdb36bc?w=1200&auto=format&fit=crop&q=80'
    ],
    googleMapsUrl: 'https://www.google.com/maps/search/?api=1&query=Los+Gigantes+Santiago+del+Teide+Tenerife',
    directionsUrl: 'https://www.google.com/maps/dir/?api=1&destination=Los+Gigantes+Santiago+del+Teide+Tenerife',
    permitInfo: 'Espacio protegido Red Natura 2000. Permiso especial del Cabildo Insular con 15 días laborables.',
    scoutingNotes: {
      soundConditions: 'Ruidoso (requiere doblaje / foley)',
      powerSupply: 'Solo generadores portátiles insonorizados a batería o gasolina',
      bestLightTime: 'Puesta de sol y hora dorada orientada al oeste (18:30 a 20:15)',
      parkingAccess: 'Aparcamiento en mirador superior a 200m; acceso final a pie con sendero'
    },
    addedBy: {
      id: 'current-user-fest',
      name: 'Ancor Ayoze',
      role: 'Dirección de Cine',
      avatar: 'https://images.unsplash.com/photo-1535713875002-d1d0cf377fde?w=400&auto=format&fit=crop&q=80'
    },
    createdAt: '09 Octubre, 2025'
  },
  {
    id: 'loc-4',
    title: 'Bosque de Niebla y Hayedo Centenario del Valle',
    category: 'naturaleza',
    categoryLabel: 'Naturaleza & Paisajes',
    address: 'Carretera Forestal SG-114 km 8, 40160 Riaza, Segovia',
    city: 'Segovia',
    postalCode: '40160',
    description: 'Espeso bosque de hayas milenarias con alfombras de hojas rojizas, troncos tapizados de musgo esmeralda y frecuentes bancos de niebla matinal. Escenario cinematográfico de cuento oscuro, misterio nórdico o cine fantástico.',
    photos: [
      'https://images.unsplash.com/photo-1448375240586-882707db888b?w=1200&auto=format&fit=crop&q=80',
      'https://images.unsplash.com/photo-1473448912268-2022ce9509d8?w=1200&auto=format&fit=crop&q=80',
      'https://images.unsplash.com/photo-1511497584788-87676104235f?w=1200&auto=format&fit=crop&q=80'
    ],
    googleMapsUrl: 'https://www.google.com/maps/search/?api=1&query=Hayedo+de+la+Pedrosa+Riaza+Segovia',
    directionsUrl: 'https://www.google.com/maps/dir/?api=1&destination=Hayedo+de+la+Pedrosa+Riaza+Segovia',
    permitInfo: 'Autorización medioambiental de Castilla y León. Prohibido fuego y pirotecnia.',
    scoutingNotes: {
      soundConditions: 'Silencioso (ideal sonido directo)',
      powerSupply: 'Baterías móviles recomendadas (Goal Zero / Ecoflow)',
      bestLightTime: 'Primeras horas de la mañana con niebla baja (07:30 a 10:00)',
      parkingAccess: 'Área recreativa a 300 metros con espacio para 8 vehículos'
    },
    addedBy: {
      id: 'part-3',
      name: 'Sofía Valdés',
      role: 'Guion y Dramaturgia',
      avatar: 'https://images.unsplash.com/photo-1544005313-94ddf0286df2?w=400&auto=format&fit=crop&q=80'
    },
    createdAt: '08 Octubre, 2025'
  },
  {
    id: 'loc-5',
    title: 'Callejón de Piedra y Pasaje Gótico del Casco Antiguo',
    category: 'urbano',
    categoryLabel: 'Urbano & Arquitectura',
    address: 'Carrer del Bisbe 1, 08002 Barcelona',
    city: 'Barcelona',
    postalCode: '08002',
    description: 'Emblemático pasaje empedrado con puente gótico elevado flanqueado por muros de piedra labrada medieval. Luz de farolas cálidas al anochecer creando sombras cinematográficas marcadas.',
    photos: [
      'https://images.unsplash.com/photo-1516483638261-f4dbaf036963?w=1200&auto=format&fit=crop&q=80',
      'https://images.unsplash.com/photo-1509356843151-3e7d96241e11?w=1200&auto=format&fit=crop&q=80'
    ],
    googleMapsUrl: 'https://www.google.com/maps/search/?api=1&query=Carrer+del+Bisbe+1+Barcelona',
    directionsUrl: 'https://www.google.com/maps/dir/?api=1&destination=Carrer+del+Bisbe+1+Barcelona',
    permitInfo: 'Corte de calle peatonal gestionado por Barcelona Film Commission. Rodaje nocturno recomendado.',
    scoutingNotes: {
      soundConditions: 'Moderado (ruido urbano controlable)',
      powerSupply: 'Puntos de conexión en comercios colaboradores o batería',
      bestLightTime: 'Horario nocturno de 23:00 a 05:00 con control total de iluminación',
      parkingAccess: 'Zona de carga y descarga en Vía Laietana a 150m'
    },
    addedBy: {
      id: 'part-4',
      name: 'David Salgado',
      role: 'Producción Audiovisual',
      avatar: 'https://images.unsplash.com/photo-1500648767791-00dcc994a43e?w=400&auto=format&fit=crop&q=80'
    },
    createdAt: '07 Octubre, 2025'
  }
];
